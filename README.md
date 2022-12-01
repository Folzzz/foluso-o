# Portfolio

# packages
 - initialize 

# project steps
- create sanity folder - "backend_sanity"
    - install sanity using - npm install -g @sanity/cli
                            sanity init
    - start sanity with - sanity start - this generates an empty schema
    - create all schema and import it to the schema.js file

- create frontend_react folder
    - install react with npx create-react-app@latest 
    - edit src folder to fit
    - install all needed dependecies - npm i @sanity/client @sanity/image-url framer-motion(for animations) sass(for scss files) react-icons(for icons0)
    - create necessary folders - assets (for all project images), components, constants(constants code file), container(component of components),

- connect frontend to backend
    - creeate client.js file in src folder
    - cd to backend and run sanity manage in terminal

- higer order component - for reusing components creatively 
    - wrap all sections with a reach HOC