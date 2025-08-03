├── Controllers
    ├── AccountController.cs
    ├── AuthorController.cs
    ├── BookAuthorController.cs
    ├── BookController.cs
    ├── CategoryController.cs
    ├── FloorController.cs
    ├── HomeController.cs
    ├── PublisherController.cs
    ├── RoleController.cs
    ├── ShelfController.cs
    └── UserRoleController.cs
├── IRepositories
    └── IGenericRepositries.cs
├── Migrations
    ├── 20250627153409_New Tables.Designer.cs
    ├── 20250627153409_New Tables.cs
    ├── 20250627195357_Remove column.Designer.cs
    ├── 20250627195357_Remove column.cs
    ├── 20250627210334_setNullOnDelete.Designer.cs
    ├── 20250627210334_setNullOnDelete.cs
    ├── 20250703163339_AddAuthTable.Designer.cs
    ├── 20250703163339_AddAuthTable.cs
    └── LibraryContextModelSnapshot.cs
├── ModelView
    ├── BookAuthorModelView.cs
    ├── BookModelView.cs
    ├── CategoryViewModel.cs
    ├── FloorViewModel.cs
    ├── LoginViewModel.cs
    ├── PublisherModelView.cs
    ├── RegisterUserViewModel.cs
    ├── RoleViewModel.cs
    ├── ShelfModelView
    │   └── AddShelfViewModel.cs
    └── UserRolesViewModel.cs
├── Models
    ├── ApplicationUser.cs
    ├── Author.cs
    ├── Book.cs
    ├── Borrowing.cs
    ├── Category.cs
    ├── Employee.cs
    ├── ErrorViewModel.cs
    ├── Floor.cs
    ├── LibraryContext.cs
    ├── Publisher.cs
    ├── Shelf.cs
    ├── User.cs
    └── UserPhone.cs
├── MvcITIProject.csproj
├── MvcITIProject.csproj.user
├── Program.cs
├── Properties
    └── launchSettings.json
├── Repositories
    ├── AuthorRepository.cs
    ├── BookRepository.cs
    ├── CategoryRepository.cs
    ├── GenericRepositries.cs
    ├── PublicherRepository.cs
    ├── PublisherRepository.cs
    └── ShelfRepository.cs
├── UnitOfWorks
    └── UnitOfWork.cs
├── Views
    ├── Account
    │   ├── Login.cshtml
    │   ├── Register.cshtml
    │   └── RegisterForAdmins.cshtml
    ├── Author
    │   ├── Add.cshtml
    │   ├── AddView.cshtml
    │   ├── Details.cshtml
    │   └── ShowAll.cshtml
    ├── Book
    │   ├── Add.cshtml
    │   ├── Delete.cshtml
    │   ├── Details.cshtml
    │   ├── Edit.cshtml
    │   └── Index.cshtml
    ├── BookAuthor
    │   └── AddView.cshtml
    ├── Category
    │   ├── Create.cshtml
    │   ├── Delete.cshtml
    │   ├── Details.cshtml
    │   ├── Edit.cshtml
    │   └── Index.cshtml
    ├── Floor
    │   ├── Create.cshtml
    │   ├── Delete.cshtml
    │   ├── Details.cshtml
    │   ├── Edit.cshtml
    │   └── Index.cshtml
    ├── Home
    │   ├── Index.cshtml
    │   └── Privacy.cshtml
    ├── Publisher
    │   ├── Create.cshtml
    │   ├── Delete.cshtml
    │   ├── Details.cshtml
    │   ├── Edit.cshtml
    │   └── Index.cshtml
    ├── Role
    │   ├── Create.cshtml
    │   └── List.cshtml
    ├── Shared
    │   ├── Error.cshtml
    │   ├── _Layout.cshtml
    │   ├── _Layout.cshtml.css
    │   └── _ValidationScriptsPartial.cshtml
    ├── Shelf
    │   ├── AddViewShelf.cshtml
    │   ├── DeleteView.cshtml
    │   ├── EditShelfView.cshtml
    │   └── Index.cshtml
    ├── UserRole
    │   ├── Edit.cshtml
    │   └── Index.cshtml
    ├── _ViewImports.cshtml
    └── _ViewStart.cshtml
├── appsettings.Development.json
├── appsettings.json
├── bin
    └── Debug
    │   └── net9.0
    │       ├── Azure.Core.dll
    │       ├── Azure.Identity.dll
    │       ├── Castle.Core.dll
    │       ├── Humanizer.dll
    │       ├── Microsoft.AspNetCore.Cryptography.Internal.dll
    │       ├── Microsoft.AspNetCore.Cryptography.KeyDerivation.dll
    │       ├── Microsoft.AspNetCore.Identity.EntityFrameworkCore.dll
    │       ├── Microsoft.AspNetCore.Razor.Language.dll
    │       ├── Microsoft.Bcl.AsyncInterfaces.dll
    │       ├── Microsoft.Build.Framework.dll
    │       ├── Microsoft.Build.Locator.dll
    │       ├── Microsoft.Build.dll
    │       ├── Microsoft.CodeAnalysis.AnalyzerUtilities.dll
    │       ├── Microsoft.CodeAnalysis.CSharp.Features.dll
    │       ├── Microsoft.CodeAnalysis.CSharp.Workspaces.dll
    │       ├── Microsoft.CodeAnalysis.CSharp.dll
    │       ├── Microsoft.CodeAnalysis.Elfie.dll
    │       ├── Microsoft.CodeAnalysis.Features.dll
    │       ├── Microsoft.CodeAnalysis.Razor.dll
    │       ├── Microsoft.CodeAnalysis.Scripting.dll
    │       ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.dll
    │       ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.dll
    │       ├── Microsoft.CodeAnalysis.Workspaces.dll
    │       ├── Microsoft.CodeAnalysis.dll
    │       ├── Microsoft.Data.SqlClient.dll
    │       ├── Microsoft.DiaSymReader.dll
    │       ├── Microsoft.DotNet.Scaffolding.Shared.dll
    │       ├── Microsoft.EntityFrameworkCore.Abstractions.dll
    │       ├── Microsoft.EntityFrameworkCore.Design.dll
    │       ├── Microsoft.EntityFrameworkCore.Proxies.dll
    │       ├── Microsoft.EntityFrameworkCore.Relational.dll
    │       ├── Microsoft.EntityFrameworkCore.SqlServer.dll
    │       ├── Microsoft.EntityFrameworkCore.dll
    │       ├── Microsoft.Extensions.Caching.Abstractions.dll
    │       ├── Microsoft.Extensions.Caching.Memory.dll
    │       ├── Microsoft.Extensions.Configuration.Abstractions.dll
    │       ├── Microsoft.Extensions.Configuration.dll
    │       ├── Microsoft.Extensions.DependencyInjection.Abstractions.dll
    │       ├── Microsoft.Extensions.DependencyInjection.dll
    │       ├── Microsoft.Extensions.DependencyModel.dll
    │       ├── Microsoft.Extensions.Identity.Core.dll
    │       ├── Microsoft.Extensions.Identity.Stores.dll
    │       ├── Microsoft.Extensions.Logging.Abstractions.dll
    │       ├── Microsoft.Extensions.Logging.dll
    │       ├── Microsoft.Extensions.Options.dll
    │       ├── Microsoft.Extensions.Primitives.dll
    │       ├── Microsoft.Identity.Client.Extensions.Msal.dll
    │       ├── Microsoft.Identity.Client.dll
    │       ├── Microsoft.IdentityModel.Abstractions.dll
    │       ├── Microsoft.IdentityModel.JsonWebTokens.dll
    │       ├── Microsoft.IdentityModel.Logging.dll
    │       ├── Microsoft.IdentityModel.Protocols.OpenIdConnect.dll
    │       ├── Microsoft.IdentityModel.Protocols.dll
    │       ├── Microsoft.IdentityModel.Tokens.dll
    │       ├── Microsoft.NET.StringTools.dll
    │       ├── Microsoft.SqlServer.Server.dll
    │       ├── Microsoft.VisualStudio.Web.CodeGeneration.Core.dll
    │       ├── Microsoft.VisualStudio.Web.CodeGeneration.EntityFrameworkCore.dll
    │       ├── Microsoft.VisualStudio.Web.CodeGeneration.Templating.dll
    │       ├── Microsoft.VisualStudio.Web.CodeGeneration.Utils.dll
    │       ├── Microsoft.VisualStudio.Web.CodeGeneration.dll
    │       ├── Microsoft.VisualStudio.Web.CodeGenerators.Mvc.dll
    │       ├── Mono.TextTemplating.dll
    │       ├── MvcITIProject.deps.json
    │       ├── MvcITIProject.dll
    │       ├── MvcITIProject.exe
    │       ├── MvcITIProject.pdb
    │       ├── MvcITIProject.runtimeconfig.json
    │       ├── MvcITIProject.staticwebassets.endpoints.json
    │       ├── MvcITIProject.staticwebassets.runtime.json
    │       ├── Newtonsoft.Json.dll
    │       ├── NuGet.Common.dll
    │       ├── NuGet.Configuration.dll
    │       ├── NuGet.DependencyResolver.Core.dll
    │       ├── NuGet.Frameworks.dll
    │       ├── NuGet.LibraryModel.dll
    │       ├── NuGet.Packaging.dll
    │       ├── NuGet.ProjectModel.dll
    │       ├── NuGet.Protocol.dll
    │       ├── NuGet.Versioning.dll
    │       ├── System.ClientModel.dll
    │       ├── System.CodeDom.dll
    │       ├── System.Composition.AttributedModel.dll
    │       ├── System.Composition.Convention.dll
    │       ├── System.Composition.Hosting.dll
    │       ├── System.Composition.Runtime.dll
    │       ├── System.Composition.TypedParts.dll
    │       ├── System.Configuration.ConfigurationManager.dll
    │       ├── System.IdentityModel.Tokens.Jwt.dll
    │       ├── System.Memory.Data.dll
    │       ├── System.Reflection.MetadataLoadContext.dll
    │       ├── System.Runtime.Caching.dll
    │       ├── System.Security.Cryptography.ProtectedData.dll
    │       ├── af
    │           └── Humanizer.resources.dll
    │       ├── appsettings.Development.json
    │       ├── appsettings.json
    │       ├── ar
    │           └── Humanizer.resources.dll
    │       ├── az
    │           └── Humanizer.resources.dll
    │       ├── bg
    │           └── Humanizer.resources.dll
    │       ├── bn-BD
    │           └── Humanizer.resources.dll
    │       ├── cs
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── da
    │           └── Humanizer.resources.dll
    │       ├── de
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── dotnet-aspnet-codegenerator-design.dll
    │       ├── el
    │           └── Humanizer.resources.dll
    │       ├── es
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── fa
    │           └── Humanizer.resources.dll
    │       ├── fi-FI
    │           └── Humanizer.resources.dll
    │       ├── fr-BE
    │           └── Humanizer.resources.dll
    │       ├── fr
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── he
    │           └── Humanizer.resources.dll
    │       ├── hr
    │           └── Humanizer.resources.dll
    │       ├── hu
    │           └── Humanizer.resources.dll
    │       ├── hy
    │           └── Humanizer.resources.dll
    │       ├── id
    │           └── Humanizer.resources.dll
    │       ├── is
    │           └── Humanizer.resources.dll
    │       ├── it
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── ja
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── ko-KR
    │           └── Humanizer.resources.dll
    │       ├── ko
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── ku
    │           └── Humanizer.resources.dll
    │       ├── lv
    │           └── Humanizer.resources.dll
    │       ├── ms-MY
    │           └── Humanizer.resources.dll
    │       ├── mt
    │           └── Humanizer.resources.dll
    │       ├── nb-NO
    │           └── Humanizer.resources.dll
    │       ├── nb
    │           └── Humanizer.resources.dll
    │       ├── nl
    │           └── Humanizer.resources.dll
    │       ├── pl
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── pt-BR
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── pt
    │           └── Humanizer.resources.dll
    │       ├── ro
    │           └── Humanizer.resources.dll
    │       ├── ru
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── runtimes
    │           ├── unix
    │           │   └── lib
    │           │   │   └── net6.0
    │           │   │       └── Microsoft.Data.SqlClient.dll
    │           ├── win-arm
    │           │   └── native
    │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │           ├── win-arm64
    │           │   └── native
    │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │           ├── win-x64
    │           │   └── native
    │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │           ├── win-x86
    │           │   └── native
    │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │           └── win
    │           │   └── lib
    │           │       └── net6.0
    │           │           ├── Microsoft.Data.SqlClient.dll
    │           │           └── System.Runtime.Caching.dll
    │       ├── sk
    │           └── Humanizer.resources.dll
    │       ├── sl
    │           └── Humanizer.resources.dll
    │       ├── sr-Latn
    │           └── Humanizer.resources.dll
    │       ├── sr
    │           └── Humanizer.resources.dll
    │       ├── sv
    │           └── Humanizer.resources.dll
    │       ├── th-TH
    │           └── Humanizer.resources.dll
    │       ├── tr
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       ├── uk
    │           └── Humanizer.resources.dll
    │       ├── uz-Cyrl-UZ
    │           └── Humanizer.resources.dll
    │       ├── uz-Latn-UZ
    │           └── Humanizer.resources.dll
    │       ├── vi
    │           └── Humanizer.resources.dll
    │       ├── zh-CN
    │           └── Humanizer.resources.dll
    │       ├── zh-Hans
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
    │       └── zh-Hant
    │           ├── Humanizer.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │           ├── Microsoft.CodeAnalysis.Features.resources.dll
    │           ├── Microsoft.CodeAnalysis.Scripting.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │           └── Microsoft.CodeAnalysis.resources.dll
