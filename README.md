# AngularCustomPipe

Projenin [Angular CLI](https://github.com/angular/angular-cli) version 14.1.1.

## Development server

Terminalden `ng serve` dendikten sonra  `http://localhost:4200/`. adresinden uygulamanın çalışma anına geçilebilir

## Absolute Path
TypeScript tarafında import pathleri kısaltmak istiyorisek tsconfig.json dosyasında kısaltmak istediğimiz service ler için tanımlama yapmamız lazım ondan sonra import da bu tanımlamaları kullanabiliriz
 ```  
"compilerOptions": {
    "baseUrl": "./",
    "paths": {
      "@environments/*": ["./src/environments/*"]
    },
    -------
}
 ```

 sonrasında ki kullanımı
  ```  
 import { environment } from '@environments/environment';
  ```
