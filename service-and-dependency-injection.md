# Service & Dependency Injection

## Service
Service is a typescript class. It makes our code to be reusable in multiple component. It can be used by helping of depenency injection. For example 
1. We have user component, within the component we have 20 methods. Each method should implement error log in case the error occurs. By the scenario, we have to create error log code 20 times. Imagine if we have plenty components. How many error code log need to be rewrite
