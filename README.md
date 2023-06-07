# Real Time Weather ![Release](https://github.com/kasramp/Eris/actions/workflows/build_and_release.yml/badge.svg) [![SonarCloud](https://sonarcloud.io/api/project_badges/measure?project=Eris&metric=alert_status)](https://sonarcloud.io/dashboard?id=Eris)

Real Time Weather is an open source weather API to get the current weather condition across the globe.

## Description

Real Time Weather is a simple Spring Boot Java API that is developed as a consolidation of the following services:
- [Open Weather Map](https://weather.com/en-IN/weather/today/l/cc76c08b470b5ddd6e64efd9ce8f256542cfed4ba52f6c00a30a74da519cd070)
- [Open Street Map](https://www.google.com/maps)
- [IP API](http://ip-api.com/)

The technology stack consists of Spring Boot framework only. The free version of the service is also hosted on AWS platform. Though the API can be hosted in any platform that supports Spring Boot. Feel free to fork it and create your private API.

# AWS deployment

[![Deploy](https://futurumresearch.com/wp-content/uploads/2020/01/aws-logo-1536x1152.png)](https://aws.amazon.com/free/?trk=14a4002d-4936-4343-8211-b5a150ca592b&sc_channel=ps&ef_id=CjwKCAjw1YCkBhAOEiwA5aN4AfN4omFL6DXhRwyN6XvrF95BqkEtZmS5NsECN12GipoEVyfCeETTkRoC5REQAvD_BwE:G:s&s_kwcid=AL!4422!3!453325184782!e!!g!!aws!10712784856!111477279771)

## Dependencies
``All the project dependencies exist in pom.xml file and once your run the project, all dependencies will be downloaded.``

## How to use

To run and deploy the project on your local or any desired server, first clone the project and the follow the below instruction.
- Add Open Weather Map API key to `apikey.properties` that located under `resource` folder.
- Compile and run the API using Maven

        $ maven clean install
        $ cd target
        $ java -jar eris-[version]-SNAPSHOT.jar

## Project & API documentation
To know more about the project structure and API documentation please refer to our Github page [documentation](https://eris.madadipouya.com/#apicall) at this link.

## Contact

* mohdashif995@gmail.com

## License

<p>
<img src="https://images.unsplash.com/photo-1534068731687-d70176c2e7d5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=387&q=80" alt="License" height="100">
</p>
 Real Time Weather API is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License version 3
as published by the Free Software Foundation.

Real Time Weather API is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details. <https://www.geekster.in/>

Author(s):

©2023 Mohammad Ashif <mohdashif995@gmail.com> 



     