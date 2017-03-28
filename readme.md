# Spiral Framework, Table of Contents
[![License](https://poser.pugx.org/spiral/framework/license)](https://packagist.org/packages/spiral/framework) 

* Overview
	* [Installation and Configuration](installation.md)
	* [Contributing](contributing.md)
	* [License](license.md)  	
* Framework
    * [Container, Factory, DI](framework/container.md)
    * [Components and IoC Scope](framework/components.md)
    * [ServiceLocator Shortcuts](framework/shortcuts.md)
    * [Bootloaders](framework/bootloaders.md)
    * [Shared Memory](framework/memory.md)
    * [Configs Objects](framework/configs.md)
    * [Modules](framework/modules.md)
* Application
	* [Directory Structure](application/directories.md)
	* [Startup Flow](application/startup.md)
	* - [Controllers and Cores](application/controllers.md)
	* - [Services](application/services.md)
	* - [View Templates](application/views.md)
	* - [Database Models](application/database.md)
	* - [Environment](application/environment.md)
	* - [Tests](application/testing.md)
* Http Dispatcher
	* - [PSR-7 Flow](http/flow.md)
	* - [Request and Input data](http/input.md)
	* - [Response and Response Wrapper](http/response.md)
	* - [Middlewares](http/middlewares.md)
	* - [Routing](http/routing.md)
	* [Cookies](http/cookies.md)
	* - [Http Errors](http/errors.md)
	* - [Request Validation](http/validation.md)
* Session
	* - [Overview](session/overview.md)
	* - [Working with Session](session/usage.md)
* Console Dispatcher
   	* - [Overview](console/overview.md)
   	* - [Embedded Commands](console/commands.md)
   	* - [Create Command](console/scaffolding.md)
* Debug and Profiling
	* - [Logging](debug/logging.md)
 	* - [Profiling](debug/profiling.md)
	* - [Error Handling](debug/errors.md)
* Common Components
   	* [Files](components/files.md)
   	* [Encryption](components/encrypter.md)
   	* - [DataEntity Model](components/data-entity.md)
   	* - [Security/RBAC](components/security.md)
   	* - [Code Generation](components/reactor.md)
   	* - [Validation](components/validation.md)
   	* - [Pagination](components/pagination.md)
* Internalization
   	* - [Overview](i18n/overview.md)
   	* - [Indexation](i18n/indexation.md)
   	* - [Usage in Views](i18n/views.md)
   	* - [Usage in Models](i18n/models.md)
   	* - [Usage in Controllers](i18n/controllers.md)
* Views and Engines
	* - [Overview](views/overview.md)
	* - [Twig Templates](views/twig.md)
	* - [Native Templates](views/native.md)
	* - [View Processors](views/processors.md)
* Stempler Views
	* - [Basic Usage](stempler/basics.md)
 	* - [Extended Usage (widgets tags, tips'n'tricks)](stempler/expert.md)
   	* - [Dark Syntax](stempler/dark.md)
* Database Layer
	* - [Overview](database/overview.md)
	* - [Query Builders](database/buidlers.md)
	* - [Schema Introspection](database/introspection.md)
	* - [Schema Declaration](database/declaration.md)
	* - [Migrations](database/migrations.md)
* Static Analysis/Tokenizer
	* - [Looking for Classes](tokenizer/classes.md)
	* - [Looking for Invocations](tokenizer/invocations.md)
	* - [PHP Code Isolation](tokenizer/isolation.md)
* ORM Engine
	* - [Overview](orm/overview.md)
	* - [Record and RecordEntity](orm/entities.md)
	* - [Transactions](orm/transactions.md)
	* - [Sources and Selectors](orm/repositories.md)
	* - [Relationships](orm/relationships.md)
	* - [Eager loading and Entity map](orm/loading.md)
	* - [Relations to Interfaces](orm/late-binding.md)
	* - [ODM Bridge](orm/odm-bridge.md)
	* - [Recursive Relations](orm/recursive.md)
* ODM Engine
	* - [Overview](odm/overview.md)
	* - [Documents and Databases](odm/entities.md)
	* - [Sources and Selectors](orm/repositories.md)
	* - [Compositions and Aggregations](odm/oop.md)
	* - [Inheritance](odm/inheritance.md)
* Storage Manager
  	* - [Overview](storage/overview.md)
  	* - [Buckets and Servers](storage/entities.md)
   	* - [Server Configuration](storage/servers.md)
   	* - [Uploading Files](storage/uploading.md)
* External Modules
	* - [Authorization](modules/auth.md)
	* - [Vault Core](modules/vault.md)
	* - [Toolkit](modules/toolkit.md)
	* - [Scaffolder](modules/scaffolder.md)
	* - [IDE helper](modules/ide-helper.md)
	* - [Cache Bridges](modules/cache.md)