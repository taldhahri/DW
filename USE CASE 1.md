Title: vulnerability and license information
Primary actor: corporate manager
Goal: analyze the vulnerability and license information from the project information retrieved over the request query passed.
Role (corporate manager): to receive project information. 
Role (corporate developer): to provide file/package information retrieved from external source.
 Precondition: Relevant file/package is available and the information on project is available.
Pass condition: accurate information on the project about the associated vulnerabilities and license information can be retrieved from querying the database.
Fail condition: wrong information retrieved from the organization database for requested file/package.
Trigger: Code check in
