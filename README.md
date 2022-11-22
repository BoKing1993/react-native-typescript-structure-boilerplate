# react-native-typescript-structure-boilerplate
Suggestion of folder and component file structure in react native, typescript, graphql project

## Folder structure
```sh
 ├── API
      ├── RestApi                     // Rest apis
      ├── GraphQL                     // Graphql apis
          ├── Crypto
              ├── Query
              ├── Mutation
      ├── Assets       	              // Images, Videos, htmls
          ├── Images       	       
          ├── Htmls    
          ├── Videos   	             
      ├── Components                  // Global components
      ├── Config       	              // Configurations
      ├── Constants       	      // Global constants
      ├── Contexts       	      // Contexts
      ├── Hocs 			      // Global hocs
      ├── Hooks                       // Global hooks
      ├── Navigation                  // Navigation settings
      ├── Redux       	              // Store, Reducers, Sagas
          ├── Reducers       	      
          ├── Sagas       	       
          ├── Store.ts       	       
          ├── index.ts       	      
      ├── Screen                      // Screen components
      ├── Services                    // Global services
      ├── Styles                      // Global styles
      ├── Types                       // Global types
      ├── Utils                       // Global utilities
```

## File structure
```sh
├── component
    ├── Importing code block 
        ├── Import from npm packages
        ├── Import global components, services, constants, styles …
        ├── Import local components, data, styles
    ├── Define types 
    ├── Define component function
    ├── JS code block
        ├── Define props/route params variables
        ├── Define variables from react hooks
        ├── Define custom variables
        ├── useEffect hooks
        ├── Define custom functions
    ├── UI code block
    ├── Define styles
```
