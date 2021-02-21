# openaq-api
This is a REST API to retrieve information from the OpenAQ LCS REST service. For more information you can visit https://docs.openaq.org/.


## Build Setup

Normally you will use this project as a dependency in your Nuxt.js, Vue.js project, to query the REST service. And the REST API will be automatically be generated from the openAPI spec file which specifies the REST service.

I you want to build it manually you can checkout the repository. After you execute npm install, the prepare script will run automatically to generate a REST API client using axios and typescript.

```bash
# install dependencies
$ npm install
```
