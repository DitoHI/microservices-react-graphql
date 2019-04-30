### Microservices of GraphQL and React

The implementation of microservices from front-end and back-end

Prerequisites
--------
1. The containers used here is the custom image from my own version. You must use your own images
2. Install `kubectl` and `docker` CLI
3. Register to Google Cloud and use the google cloud computer. You must apply for the billing to use the service

DevOps Dependencies
--------

* K8s
* Minikube (run K8s locally)
* Ambassador (mapping internal cluster to external)
* Docker
* Google Compute Engine

Back End Dependencies
--------

* Create user with default value `isActived` false
* Show all users with flexibly request of parameters. You just can request user based on name, email, or nothing at all
* Update user with the only one `isActived` true
* Delete user by its parameters
* Use [this library](https://github.com/okgrow/graphql-scalars) from @okgrow to use Scalar Type in GraphQL


Front End Dependencies
--------

* React with Bootstrap 4.x implemented (Reactstrap)
* React Icons
* React Slick
* Redux
* Aphrodite


Deployment
--------

* (Unactive) External API of Google Cloud: [35.200.175.130](http://35.200.175.130)
* (Temporary) Deployed to Azure App Service to see the result. See the details in [here](https://github.com/DitoHI/react-cosmosdb-graphql)


License
--------

    Copyright 2019 Dito Hafizh Indriarto

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated 
    documentation files (the "Software"), to deal in the Software without restriction, including without 
    limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the 
    Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial 
    portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT 
    NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
    WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE 
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.