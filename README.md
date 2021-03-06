
## LAYERS

### 1) Business Layer
 
#### - Abstract Classes
1. [IBrandService.cs](https://github.com/iremerol/RentACarProject/blob/main/Business/Abstract/IBrandService.cs)
2. [ICarService.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Abstract/ICarService.cs)
3. [IColorService.cs](https://github.com/iremerol/RentACarProject//blob/master/Business/Abstract/IColorService.cs)
4. [ICustomerService.cs](https://github.com/iremerol/RentACarProject//blob/master/Business/Abstract/ICustomerService.cs)
5. [IRentalService.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Abstract/IRentalService.cs) 
6. [IUserService.cs](https://github.com/iremerol/RentACarProject//blob/master/Business/Abstract/IUserService.cs)

#### - Concrete Classes
1. [CarManager.cs](https://github.com/iremerol/RentACarProject/blob/main/Business/Concrete/CarManager.cs)
2. [BrandManager.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Concrete/BrandManager.cs)
3. [ColorManager.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Concrete/ColorManager.cs)
4. [CustomerManager.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Concrete/CustomerManager.cs)
5. [CustomerManager.cs](https://github.com/iremerol/RentACarProject/blob/main/Business/Concrete/CustomerManager.cs)
6. [RentalManager.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Concrete/RentalManager.cs)
  
 
#### - Constants Classes

1. [Messages.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/Constants/Messages.cs)

#### - DependencyResolvers
1. [AutofacBusinessModule.cs](https://github.com/iremerol/RentACarProject/blob/main/Business/DependencyResolvers/Autofac/AutofacBusinessModule.cs)

#### - FluentValidation
1. [CarValidator.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/ValidationRules/FluentValidation/CarValidator.cs)
2. [RentalValidator.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/ValidationRules/FluentValidation/RentalValidator.cs)
3. [UserValidator.cs](https://github.com/iremerol/RentACarProject/blob/master/Business/ValidationRules/FluentValidation/UserValidator.cs)
