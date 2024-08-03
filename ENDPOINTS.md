# AUTH-MS

## Endpoints

### AUTH-MS

##### Mutation 

- `Login` - Iniciar Sesion                            - IMPLEMENTADO
- `SignupClient` - Registrar un coordinador           - IMPLEMENTADO
- `SignupProfessional` - Registrar un profesioanl     - IMPLEMENTADO

##### Query 

- `revalidateToken` - Registrar un profesioanl        - IMPLEMENTADO

### CLIENT-MS

---
#### Client
##### Mutation
- `createUser` - Crear un usuario para el coordinador logueado
- `updateUser` - Actualizar informacion del usuario logueado           - IMPLEMENTADO
- `deleteUser` - Eliminar un usuario del coordinador logueado         - IMPLEMENTADO

##### Query 
- `Client` - Obtener informacion del coordinador logueado               - IMPLEMENTADO
- `findUsers` - Obtener todos los usuarios del coordinador logueado     - IMPLEMENTADO

---
#### Patient
##### Mutation
- `createPatient` - Crear un paciente para el coordinador           - IMPLEMENTADO
- `updatePatient` - Actualizar informacion del paciente             - IMPLEMENTADO
- `deletePatient` - Eliminar un paciente del coordinador/usuario  - IMPLEMENTADO

##### Query
- `findPatients` - Obtener todos los pacientes del coordinador/usuario logueado     - IMPLEMENTADO                    
- `findPatient` - Obtener un paciente del coordinador logueado                      - IMPLEMENTADO
- `findPatientByCompany` - Obtener todos los pacientes de una empresa               - IMPLEMENTADO

---
#### Company
##### Mutation
- `createCompany` - Crear una empresa para el coordinador           - IMPLEMENTADO
- `updateCompany` - Actualizar informacion de la empresa            - IMPLEMENTADO       
- `deleteCompany` - Eliminar una empresa del coordinador/usuario   - IMPLEMENTADO

##### Query
- `findCompanies` - Obtener todas las empresas del coordinador/usuario logueado     - IMPLEMENTADO                    
- `findCompany` - Obtener una empresa del coordinador logueado                      - IMPLEMENTADO

---
#### Treatment
##### Mutation
- `createTreatment` - Crear una prestacion para el coordinador          - IMPLEMENTADO
- `updateTreatment` - Actualizar informacion de la prestacion           - IMPLEMENTADO
- `deleteTreatment` - Eliminar una prestacion del coordinador/usuario   - IMPLEMENTADO

##### Query
- `findTreatments` - Obtener todas las prestaciones del coordinador/usuario logueado    - IMPLEMENTADO
- `findTreatment` - Obtener una prestacion del coordinador logueado                     - IMPLEMENTADO    

---
#### Company Has Treatment
##### Mutation
- `createCompanyTreatment` - Crear una relacion para el coordinador           - IMPLEMENTADO          
- `updateCompanyTreatment` - Actualizar informacion de la relacion            - IMPLEMENTADO
- `deleteCompanyTreatment` - Eliminar una relacion del coordinador/usuario    - IMPLEMENTADO

##### Query
- `findTreatmentsByCompany` - Obtener todas las relaciones de una empresa     - IMPLEMENTADO
- `findTreatmentByCompany` - Obtener el valor de una relacion de una empresa  - IMPLEMENTADO

---
#### Treatment Has Professional
##### Mutation
- `createTreatmentProfessional` - Crear una relacion para el coordinador                     
- `updateTreatmentProfessional` - Actualizar informacion de la relacion             - IMPLEMENTADO
- `deleteTreatmentProfessional` - Eliminar una relacion del coordinador/usuario     - IMPLEMENTADO

##### Query
- `findTreatmentsByProfessional` - Obtener todas las relaciones de una empresa      - IMPLEMENTADO
- `findTreatmentByProfessional` - Obtener el valor de una relacion de una empresa   - IMPLEMENTADO