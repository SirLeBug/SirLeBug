## Hi there 👋

<!--
**SirLeBug/SirLeBug** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```C#
class AboutMe() {

  const string fullName = "Daniel Sanz"
  const string[] hobbies = {"Videogames", "IT Technology Software"};
  string field = "";
  var year = DateTime.Now.Year;

  public string currentField()
  {
    switch(year) 
    {
      case 2017:
        return "Technician in Microcomputer Systems and Networks";
        break;
      case 2020:
        return "Web Application Developer";
        break;
      case 2022:
        return "Multiplatform Application Developer";
        break;
      case 2024:
        return "Videogame Developer";
        break;
      default:
        return "Videogame Enthusiast";
        break;
    }
  }

  static void Main(string[] args)
    {
      AboutMe me = new AboutMe();
      me.field = currentField();

      Console.WriteLine("Hi, my name is " + fullName + " my interests mostly consist of "
        + hobbies[0] + " and also " + hobbies[1] +". I am currently an emerging " + field +
        ", I hope you enjoy your stay.");
    }

}
```
