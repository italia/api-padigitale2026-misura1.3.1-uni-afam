# Release note
# Version 2.1.0
Versione finale per l'asseverazione


# Version 2.0.6 
- [GUIDE] updated the readme.md file with the new e-services' names and uploaded the guide for publishing the e-services
- [IFS04.1, IFS05.1] The field 'degree_course_code' has been added to the request to specify the enrollment or qualification referenced by the change request
- [IFS04.4, IFS05.4] Fix swagger
- [IFS02] Removed the 'required' constraint from the degree_class_code attribute in the proof_enrollment object
- [IFS04.4, IFS05.4] Removed the 'required' constraint from the attribute_name of the issue
- [IFS02] issue #189, fixed yaml file the proof_education_course strcture 
- [IFS03] issue #189 - fixed yaml file the  proof_qualifications_level + proof_qualifications_diploma_supplement
- [IFS02][IFS03][IFS04][IFS05] issue #200 - fixed regex for family_name and given_name 
- [IFS02][IFS03][IFS04][IFS05] issue #199 - fixed regex for tax_code
- [IFS03] issue #197 #198 - fixed yaml file for required fields naming "proof_qualifications_level" and "proof_qualifications_diploma_supplement"
- [IFS09] issue #193 - set minimum for fields female_enrollment_count and  male_enrollment_count set to 0
- [IFS04.2][IFS05.2] issue #191 - Update output response message
- [GUIDE] issue #191 - updated the readme.md file with details about response_code and file_status for IFS04/05
- [IFSX] issue #203 - Added the grade value expressed in floating point
- [IFS09] issue #195 - Removed the requirement for degree_class_code and we are making degree_course_code nullable, so you can consolidate all counts into an item without degree_course_code (as indicated by the MUR in the CINECA repository) with a null value.
- [IFS01] issue #125: updated learning hours from 1 to 0"
- [IFS0X] issues  #196, #207 fixed isee_min and max type and grading_scale min and max type, set nullable any attribute for the APIs SDG
- [IFS05] issue #211, fixed change_requests_status from object to array
- [Readme.md]  Issue #212: Added on the documentation a reference to the security profile in accordance with the AgID Interoperability guidelines for the implementation of e-service.Avoid to activate the Audit profile when you publish the e-service https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/issues/212
- [IFS06] issue #214: fixed operationId value of the path '/student-enrollments-changes'  
- [IFS07] Issue #215: Updated the definitions for academic_system and sync_mode by removing the min and max constraints and making these fields nullable
- [IFS02.3] 03.09.2024 issue #217
- [IFS04.2] 03.09.2024 issue #216
- [IFS01,IFS06,IFS07] 06.09.2024 fixed examples with the cursor
- [IFS0X] 12.09.2024 issue #221 Removed min and max for enum types
- [IFS0X] 12.09.2024 issue #220 Removed min and max for date types
- [IFS0X] 13.09.2024 issue #218 Modified the scale of values assigned to the SDG cases by enabling the possibility of entering greading with 'letters' (Example: from A to D).
- [IFS01, IFS06, IFS07] 17.09.2024 issue #222 Restored the management of the cursor with the filter parameters sent also in subsequent invocations
- [IFS04.4, IFS05.4] 03.10.2024 fixed the response of ifs04.4 and ifs05.4 
- [IFS04.1] 03.10.2024 issue #224 Removed the nullable property from the attribute_name parameter in IFS04.1
- [IFS04.4, IFS05.4] 03.10.2024 issue #225 fixed the required attributes in the requests for ifs04.4 and ifs05.4.
- [IFS03, IFS05] 04.10.2024 corrected a typo in the qualification_grading_scale fields, changing its type from string to number
- [IFS05.1] 08.10.2024 issue #224 Removed the nullable property from the attribute_name parameter in IFS05.1
- [IFS03, IFS08, IFS09] 10.10.2024 issue #227 Renamed the OperationID from Italian to English for consistency and clarity in the codebase
- [IFS04] 18.10.2024 fixed the null value definition in the enum file_status
- [IFS04] 23.10.2024 issue #232 fixed the null value definition in the enum file_status
- [IFS03] 23.10.2024 issue #230 fixed learning_cfu from string to number
- [IFS04, IFS05] 24.10.2024 Corrections to the specifications for adjustments to be discussed with ANIS, file status and examples, reorganized the position of the methods for symmetry between IFS04 and IFS05


## Version 2.0.5
- [IFS01.2] It was added the curriculum description of the learnings list
- [IFS04.2, IFS03.5] issue #163 - It was fixed the the file_code request parameter, it isn't mandatory in the API IFS04.2 and IFS05.2
- [IFS04.4] Issue #167 - It was fixed the example request.json on the data_request, it was removed the timestamp in the data_request_timestamp exactly how it was in the yaml
- [IFS05.4] Issue #170 - It was fixed the example request.json on the data_request, it was removed the timestamp in the data_request_timestamp exactly how it was in the yaml
- [IFS04.4] Issue #168 - Enrollments from Object to  Array in yaml IFS04 + and the examples have been updated
- [IFS05.4] Issue #169 - Qualifications from Object to Array in yaml IFS05 and the examples have been updated
- [IFS01] Issue #171 The examples with the municipality's name has changed with ISTAT code
- [IFS09] Issue #173 Fixed the endpoint name in count-academic-enrollments-by-degree-courses
- [IFS0X] The definition of the http status 400 (bad request) has been updated for each YAML
- [IFS0X] The definition of the http status 404 (missing resource) has been removed from each YAML file.
- [IFS03.1] Removed the required attribute to the tax_code parameter
- [IFS07] Filter parameters have been added 
        1. new/old University System (university_system_type)
        2. full or the incremental mode (syncmode)
- [IFS02.3] Issue #175 The structure of the proof_education_course object has been changed from an object to an array
- [IFS02, IFS03] The API was updated to make the tax_code mandatory in the request, while the person_id is recommended
- [IFS03.4] Issue #176 it was added enum for the field administering_institute_status
- [IFS03.4] Issue #179 it was fixed the YAML definition schema from object to array ("proof_qualifications_diploma_supplement")
- [IFS03.3] Issue #178 The structure of the proof_qualifications_level object has been changed from an object to an array
- [IFS02.3, IFS03.3, IFS03.4] It has fixed issue #180 by updating the README with the proposed changes
- [FIS01.2] Provide instructions in the README on how to manage optional courses in the educational offer
- [IFS02.1] Removed attribute Institute_Name in the response message (06/06/2024)
- [IFS03.1] Removed attribute Institute_Name in the response message (06/06/2024)
- [IFS06.1] Converted the GET request in POST (06/06/2024)
- [IFS07.1] Converted the GET request in POST (06/06/2024)
- [IFS07.1] Renamed attribute univerity_system_type in academic_system in the response message (06/06/2024)



## Version 2.0.4 

- [IFS03.1] Removed the required condition on the attribute qualification_name in the response
- [IFS03.1] Added the required to the qualification_grade_value
- [IFS04] Added the response_code attribute in the response of the methods IFS04.1 and IFS04.3
- [IFS05] Added the response_code attribute in the response of the methods IFS05.1 and IFS04.3
- [IFS0X] It was updated the max length of type_programme_code and cursor attributes
- [Readme.md] It was fixed the ref to the IFS08 yaml in the readme.md file
- [IFS01] It was fiexed the examples in the yaml file
- [Readme.md] It was updated the IFS01 descriptions
- [IFS01.2] It was added the cursor pagination even for the detail educational offering detail
- [Readme.md, IFS01, IFS02, IFS03] Severals updates with feedbacks required by the work group 1.3.1 Università and AFAM 

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/2.0.4

## Version 2.0.3

- Removed the degree_class_code attribute from IFS01 and corrected the example in the issue services IF04 and IFS05
- It was added the release note file
- Have been added the examples of use cases in readme.md file
- Changed the requests body of API for SDG use cases
- Have been added the ISEE bands for API IFS08 on the readme.md file
- Removed the institute_code attribute from IFS02-IFS03 SDG Methods 
- Added "learning_cfu" Attribute in IFS03.4 Response 
- Added the vote value rule: ^(\d{1,3}|(\d{1,3}[L]?)|\bQUALIFIED\b)$

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/2.0.3

## Version 2.0.2

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/2.0.2

## Version 2.0.1

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/2.0.1

## Version 2.0.0

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/2.0.0

## Version 1.0.1

- IFS02.1 & IFS03.1 con descrizioni di corso, classe e tipo corso
- fix IDANPR (personID) pattern

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/1.0.1

## Version 1.0.0

- IFS02.1 Iscrizioni ANIS con descrizioni dei vocabolari + parte SDG DONE
- IFS03.1 Titoli ANIS con descrizioni dei vocabolari +parte SDG DONE
- IFS06.1 DONE
- IFS07.1 DONE

https://github.com/italia/api-padigitale2026-misura1.3.1-uni-afam/releases/tag/1.0.0
