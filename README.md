# RockSDK_7.4
Rock SDK 7.4

Steps to Start

Requirements Visual Studio, IIS Express, and MSSQL Express

1.) Open the Rockit.sln solution file
2.) Drop a web.ConnectionStrings.config file in the RockWeb directory
  <connectionStrings>
  <add name="RockContext" connectionString="Data Source=WINDOWS10-NAME\SQLEXPRESS;Initial Catalog=RockDB; User Id=sa; password=password;MultipleActiveResultSets=true" providerName="System.Data.SqlClient"/>
</connectionStrings>
3.) Drop an empty Run.Migration file in App_Data
4.) Launch Rock!

