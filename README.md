```c
typedef struct {
    const char* name;
    const char* email;
    const char* website;
} About;

typedef struct {
    About about;
    const char* languages[2];
    const char* tech[8];
} Developer;

Developer developer = {
    .about = {
        .name = "Gabriel Lima",
        .email = "gabriel@firewavestudios.com",
        .website = "https://trenbankai.com/"
    },
    .languages = {"Java", "Kotlin", "C#", "C", "C++", "PHP", "TS/JS", "HTML/CSS"},
    .tech = {"Godot", "VSCode", "Zed", "Visual Studio", "IntelliJ IDEA", "Rider"}
};
```
If you want to see my serious projects [here u go](https://github.com/gabriel-aplok/gabriel-aplok/blob/main/PROJECTS.md).
