
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

### 2) Core Layer
#### - DataAccess
1. [IEntityRepository.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/DataAccess/IEntityRepository.cs)
2. [EfEntityRepositoryBase.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/DataAccess/EntityFramework/EfEntityRepositoryBase.cs)

#### - Entities
1. [IDto.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/Entities/IDto.cs)
2. [IEntity.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/Entities/IEntity.cs)

#### - Utilities
##### - Interceptors
1. [AspectInterceptorSelector.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/Utilities/Interceptors/AspectInterceptorSelector.cs)
2. [MethodInterception.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/Utilities/Interceptors/MethodInterception.cs)
3. [MethodInterceptionBaseAttribute.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/Utilities/Interceptors/MethodInterceptionBaseAttribute.cs)

#### - CrossCuttingConcerns
1. [ValidationTool.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/CrossCuttingConcerns/Validation/ValidationTool.cs)


#### - Aspects
1. [ValidationAspect.cs](https://github.com/iremerol/RentACarProject/blob/master/Core/Aspects/Autofac/Validation/ValidationAspect.cs)


### 3) DataAccess Layer
#### - Abstract Classes
1. [IBrandDal.cs](https://github.com/iremerol/RentACarProjectt/blob/master/DataAccess/Abstract/IBrandDal.cs)
2. [ICarDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Abstract/ICarDal.cs)
3. [IColorDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Abstract/IColorDal.cs)
4. [ICustomerDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Abstract/ICustomerDal.cs)
5. [IUserDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Abstract/IUserDal.cs)
6. [IRentalDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Abstract/IRentalDal.cs)

#### - EntityFramework
1. [EfBrandDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/EntityFramework/EfBrandDal.cs)
2. [EfCarDal.cs](https://github.com/iremerol/RentACarProject/blob/main/DataAccess/Concrete/EntityFramework/Repository/EfCarDal.cs)
3. [EfColorDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/EntityFramework/EfColorDal.cs)
4. [EfCustomerDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/EntityFramework/EfCustomerDal.cs)
5. [EfUserDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/EntityFramework/EfUserDal.cs)
6. [EfRentalDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/EntityFramework/EfRentalDal.cs)
7. [RentACarContext.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/EntityFramework/RentACarContext.cs)

#### - InMemory
1. [InMemoryBrandDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/InMemory/InMemoryBrandDal.cs)
2. [InMemoryCarDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/InMemory/InMemoryCarDal.cs)
3. [InMemoryColorDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/InMemory/InMemoryColorDal.cs)
4. [InMemoryCustomerDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/InMemory/InMemoryCustomerDal.cs)
5. [InMemoryUserDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/InMemory/InMemoryUserDal.cs)
6. [InMemoryRentalDal.cs](https://github.com/iremerol/RentACarProject/blob/master/DataAccess/Concrete/InMemory/InMemoryRentalDal.cs)



### 4) Entities Layer
#### - Concrete Classes
1. [Brand.cs](https://github.com/iremerol/RentACarProject/blob/master/Entities/Concrete/Brand.cs)
2. [Car.cs](https://github.com/iremerol/RentACarProject/blob/master/Entities/Concrete/Car.cs)
3. [Color.cs](https://github.com/iremerol/RentACarProject/blob/master/Entities/Concrete/Color.cs)
4. [Customer.cs](https://github.com/iremerol/RentACarProject/blob/master/Entities/Concrete/Customer.cs)
5. [Rental.cs](https://github.com/iremerol/RentACarProject/blob/master/Entities/Concrete/Rental.cs)
6. [User.cs](https://github.com/iremerol/RentACarProject/blob/master/Entities/Concrete/User.cs)

#### - DTOs Classes
1. [CarDetailDto.cs](https://github.com/iremerol/RentACarProject/blob/main/Entities/DTOs/CarDetailDto.cs)
2. [RentalDetailDto.cs](https://github.com/iremerol/RentACarProject/blob/main/Entities/DTOs/RentalDetailDto.cs)


### 5) WebAPI Layer
#### - Controllers Classes
1. [BrandsController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/BrandsController.cs)
2. [CarsController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/CarsController.cs)
3. [ColorsController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/ColorsController.cs)
4. [CustomersController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/CustomersController.cs)
5. [RentalsController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/RentalsController.cs)
6. [UsersController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/UsersController.cs)
7. [WeatherForecastController.cs](https://github.com/iremerol/RentACarProject/blob/main/WebAPI/Controllers/WeatherForecastController.cs)

### 6) ConsoleUI
1. [Program.cs](https://github.com/iremerol/RentACarProject/blob/master/ConsoleUI/Program.cs)








