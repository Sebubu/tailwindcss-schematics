# @flakolefluk/tailwind-schematics
## add TailwindCSS to your Angular project

### Requirements
Currently Angular 8+ is supported

### Adding TailwindCSS to your project
```
ng add @flakolefluk/tailwind-schematics (will use default project)
// or
ng add @flakolefluk/tailwind-schematics --project=<PROJECT_NAME>
```

### Building for production
When building your project for production, Prune CSS will be used to removed all the unused utility classes generated by TailwindCSS.

### Contributing
This project is in an early stage. 
Please report any bugs and feel free to create PR's. 
Thank you!

### Unit Testing
`npm run test` will run the unit tests, using Jasmine as a runner and test framework.