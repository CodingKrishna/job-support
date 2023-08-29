UT VS IT
| Unit Test  | Integration Test |
| ------------- | ------------- |
| independent classes or functions are tested to check function in the code. | Integration testing is to find errors/success in interaction between two logical/functional units  |
| There is no layer testing  | We need to perform real operations to check all the layers are working well in the flow. Here, the layers are controller, service, repository…  |
| We need to perform mocking operations. Not real ones!  | We need not to dependent on mocks We can perform operations on real software. |
| NO E2E(end to end testing) | We can perform e2e testing |


Recommendation: We can use integration testing for api's e2e testing and UT for specific logic's in the application.


https://veeevek.medium.com/springboot-separate-unit-integration-test-336abbc38ef4#:~:text=UT%20%3D%20Unit%20Tests%20IT%20%3D%20Integration%20Tests.&text=The%20above%20link%20mainly%20focuses,and%20maven%2Dfailsafe%2Dplugin.  
https://salithachathuranga94.medium.com/unit-and-integration-testing-in-spring-boot-micro-service-901fc53b0dff  
https://www.springcloud.io/post/2022-09/spring-boot-micro-service-test/#gsc.tab=0  
