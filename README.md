![](https://4mlrta.db.files.1drv.com/y4mmLk8EHDlKkh0VI4C-77hQDBj7edWLtxKQqq-p5gzoVORVWVBOppTy0dX1bZH3D6R8rb2CB-d3Qb7a5bgViF-Adtxli2CtOIsSN0wgv6Ci-VQ5VLh8FPRyVeAoJHLKtvvKvj9R-Uk_Cohi1NG6Ei_vnHemRspTJn5HEEmZP7v5lzVkRTYmUuu_9awJRf2vF-RCj1bgFpmb1vE4CRiiecolg?width=998&height=550&cropmode=none)
# TalenTUM - SEBA Master Course Summer Term 2018
This project contains an integrated application that serves the TalenTUM business idea.
It is bulid based on MERN.io's starter package for MongoDB, Express, React and NodeJS.
I brings along preconfigured multi-language support and a production-ready environment.
Core of our work is to bulid components handling our business logic. The following functionalities already exist:
- Start Page for Individual & Corporate Users
- Profiles for all account types
- Matching for corporates and students
- Watch Lists (for Students & Companies)

We tried to encorporate all features relevant to this platform. However, it is a fictional prototype and needs to be 
considered as such.

## MERN Project - MongoDB, Express.js, React.js & NodeJS
As this is based on MongoDB, Express.js, React.js & NodeJS the whole project is managed with npm and controlled alike. 
To setup the project run "npm install" and afterwards "mongod && npm start". Ensure that MongoDB runs locally with 
standard settings. Alternatively, we will supply a remote MongoDB Cluster hosted with MongoDB Atlas. 

## Build Options 
For your convenience MERN brings along standardized Docker support. Please see the relevant commands below. 
There are docker configurations for both development and production:

To run docker for development:
```sh
docker-compose build # re-run after changing dependencies
docker-compose up
```
or, if you want to override the web port:
```sh
WEB_PORT=<your_custom_port> docker-compose up
```

To run docker for production:
```sh
docker-compose -f docker-compose-production.yml up --build
```

To reset the database:
```sh
docker-compose down --volumes
```

## Project Structure
TODO: Add project structure.

## Authors and Annotations
- Christian Becker (M.Sc. Information Systems)
- Oliver Schmidt (M.Sc. Information Systems)
- Herbert Woisetschläger (M.Sc. Information Systems)
- Thomas Binderberger (M.Sc. Information Systems)

All authors study according to the 2008 FPSO. 

Please see the [MERN Docs](http://mern.io/documentation.html) for details on the project template. 

## License
As MERN is released under the [MIT License](http://www.opensource.org/licenses/MIT) TalenTUM is as well. 
The code can be downloaded, modified and redistributed. No commercialisation is allowed. 
