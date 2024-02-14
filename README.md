```csharp
using System.Runtime.InteropServices;

public class Profile
{
    [DllImport("user32.dll")]
    public static extern int AboutMe();

    public string Name => "Stella";
    public string Discord => "yami.dev"; 
    public string Role => "Software Developer";
    public string[] Hobbies => { "Watching Anime", "Cosplaying", "Playing Video Games" };
    public string Website => "https://hylia.dev";
    public string[] Languages => { "English", "Japanese", "Polish" };
    public string GenderIdentity => "TransFem";
    public string SexualOrientation => "Bi-Sexual Furry";
    public string[] Projects => { "https://vtubers.wiki" };
    public string[] ProgrammingLanguages => { "TypeScript 100%", "C# 20%", "Python 50%", "HTML 100%", "CSS 90%", "JavaScript 100%", "C 40%" };
    public string[] Tools => { "Git", "Bootstrap", "NodeJS", "NextJS", "npm" };
}
```

