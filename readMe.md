## Description

This project is a simple Product API built in asp.net core REST API.

## Configuration

change database connection string with appsettings.json DefaultConnection property.

## Running the app

```visual studio
# Run application
```

```visual studio code
# dotnet run

```

## Implementation
	* complete all crud endpoint
	* Error handling with DTO(data transfer object) class
	* implement DI(depenency injection)

## Summary
I have implemented all features in 2 hours but I spent lots of time for visual studio environment setup.
Installing visual studio, asp .net, and MSSQL Server took 8 hours.
I have not completed unit test and e2e test so I will integrate test code after submitting project.

Thanks for your attention.

## Unit Test
	* GetProducts_Should_Be_List: get product list
	* GetProduct_Should_Be_Object: get prodct by id
	* GetProduct_Should_Not_Found: get product returns not found
	* PostProduct_Should_Be_Created: create product return object
	* PutProduct_Should_Be_Object: update product return object
	* PutProduct_Should_Be_Not_Found: update product return not found
	* DeleteProduct_Should_Be_204: delete product return no content

## test
```visual studio
# Test application
```

```visual studio code
# dotnet test