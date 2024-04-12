añadir esto en el archivo csproj

<ItemGroup>
  <PackageReference Include="Microsoft.AspNetCore.Authentication.JwtBearer" Version="8.0.4" />
  <PackageReference Include="Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="8.0.4" />
  <PackageReference Include="Microsoft.EntityFrameworkCore" Version="8.0.4" />
  <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="8.0.4" />
  <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="8.0.4">
    <PrivateAssets>all</PrivateAssets>
    <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
  </PackageReference>
  <PackageReference Include="Microsoft.IdentityModel.Tokens" Version="7.5.1" />
  <PackageReference Include="Swashbuckle.AspNetCore" Version="6.5.0" />
  <PackageReference Include="Swashbuckle.AspNetCore.Filters" Version="8.0.1" />
  <PackageReference Include="System.IdentityModel.Tokens.Jwt" Version="7.5.1" />
</ItemGroup>
