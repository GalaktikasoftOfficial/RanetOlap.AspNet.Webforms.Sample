"# RanetOlap.AspNet.Webforms.Sample" 

# Integrating Ranet OLAP PivotTable in ASP.NET Web Form Application

A lot of Ranet users need to integrate the pivot table into their ready applications, so when we developed it we tried to design the architecture that would allow developers to rewrite and add functionality to the solution according to their business needs implying ASP.NET pivot table. Still, certain issues may arise during the integration process. Thus, in this chapter we describe the very process of the integration of Ranet Pivot Table into an ASP.NET application...
See also https://galaktika-soft.com/blog/integrating-ranet-pivot-table-in-asp-net-application.html


# Possible issues and ways to solve them

## Could not find a part of the path … bin\roslyn\csc.exe
https://stackoverflow.com/questions/32780315/could-not-find-a-part-of-the-path-bin-roslyn-csc-exe

run this in the Package Manager Console:
Update-Package Microsoft.CodeDom.Providers.DotNetCompilerPlatform -r
or
Install-Package Microsoft.Net.Compilers -Version 3.3.1
