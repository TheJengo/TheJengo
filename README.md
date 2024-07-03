<!--
**TheJengo/TheJengo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<p align="center">
  <h3 align="center">👋 Welcome To the TheJengo.Program.cs</h3>
</p>

```csharp
using TheJengo.Enums;
using TheJengo.Models;

namespace TheJengo
{
  public static Program
  {
    public static Task Main()
    {
      Dictionary<Area, string[]> technologies = new()
      {
        {Area.Languages, new string []{ "C#", "Javascript", "TypeScript" "Java", "C", "PHP" }},
        {Area.Backends, new string []{ ".NET", "Laravel" }},
        {Area.Frontends, new string []{ "Angular", "Vue", "React" }},
        {Area.Databases, new string []{ "MSSQL", "Azure SQL", "MySQL", "NoSQL" }},
        {Area.Devops, new string []{ "AzureDevOps", "Docker", "Git" }},
        {Area.Interests, new string [] { "Azure", "Cloud", "Go" "Microservices", "CQRS", "Event Driven Development", "TDD", "BDD" }}
      };

      Developer dev = new 
      {
        Name = "Cengiz Cebeci",
        Previous = new List<Role>(){
            new Role("HexTransforma Healthcare", "Junior Backend Developer").
            new Role("wtw", "Software Engineer")
        },
        Current = new Role("CAI", "Software Engineer"), 
        Technologies = technologies
      };

      Console.WriteLine(dev.ToString());
    }
  }
}
```

<h3 align="center">Stats</h3>
<p align="center" width="100%">  
  <a href="https://github.com/thejengo">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=thejengo&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515" 
         />
  </a>
</p>
<h3 align="center">Social</h3>
<p align="center">
  <a href="https://www.cengizcebeci.com/"><img alt="Website" src="https://img.shields.io/badge/Website-www.cengizcebeci.com-informational?style=flat-square&logo=google-chrome&logoColor=white"></a> 
  <a href="https://www.linkedin.com/in/cengiz-cebeci/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Cengiz Cebeci-informational?style=flat-square&logo=linkedin&logoColor=white"></a> 
  <a href="https://www.instagram.com/thejengo/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-thejengo-informational?style=flat-square&logo=instagram&logoColor=white"></a> 
  <a href="https://www.twitter.com/thejengo/"><img alt="Twitter" src="https://img.shields.io/badge/Twitter-thejengo-informational?style=flat-square&logo=twitter&logoColor=white"></a> 
  <a href="mailto:swe.cengizcebeci@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-swe.cengizcebeci@gmail.com-informational?style=flat-square&logo=gmail&logoColor=white"></a> 
</p>
