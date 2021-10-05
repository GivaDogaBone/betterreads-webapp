<!--- STARTEXCLUDE --->
# BetterReads Spring App
*180 minutes, Advanced, [Start Building](https://github.com/DataStax-Examples/betterreads-webapp#quick-start)*

Companion code for the Java Brains "code with me" series that reads data from [DataStax Astra DB](https://dtsx.io/3FkFP94). The video series is located [here](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTZgMZbKkvJyr7u2repYYXE-)
<!--- ENDEXCLUDE --->

![image](https://raw.githubusercontent.com/DataStax-Examples/betterreads-webapp/master/hero.jpeg)

## Quick Start
<!--- STARTEXCLUDE --->
* [Signup for DataStax Astra](https://dtsx.io/3FkFP94), or login to your already existing account. 
* [Create an Astra DB Database](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-astra-db) if you don't already have one.
<!--- ENDEXCLUDE --->
* [Create an Astra DB Keyspace](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-astra-db-keyspace) called `sag_betterreads` in your database.
* [Generate an Application Token](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-application-token) with the role of `Database Administrator` for the Organization that your Astra DB is in.
* Click the 'Open in Gitpod' link: [![Open in IDE](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/DataStax-Examples/betterreads-webapp)
* Once the app is finished launching in the Gitpod IDE, copy the `env.example` file to a file named `.env` and fill the required values in from your Application Token and [Astra DB connection settings](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#get-your-astra-db-connection-settings).
* Activate your environment settings by running `source .env` in the Gitpod console.
* Get your [secure connect bundle](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#get-an-astra-db-secure-connect-bundle) from the connect page of your database and upload it to your Gitpod instance. Rename it to `secure-connect.zip`
* Move your `secure-connect.zip` to `src/main/resources` in the Gitpod file explorer.
* Start the example by running `./mvnw spring-boot:run` in the Gitpod console.

## Objectives
* Follow along with the Java Brains "code with me" series. The video playlist is located [here](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTZgMZbKkvJyr7u2repYYXE-).

## How this works
Once the Astra DB credentials are provided, BetterReads can connect to Astra DB.
