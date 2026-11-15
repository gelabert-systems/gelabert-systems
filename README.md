```rs
#[derive(Developer, Debug, Display)]
struct GelabertSystems {
    pronouns: (&'static str, &'static str),
    location: Country,
    stack:    Stack,
    projects: Vec<Project>,
}

const ME: GelabertSystems = GelabertSystems {
    pronouns: ("he", "him"),
    location: Country::Spain,
    stack:    Stack {
        low_level:   vec!["x86-64 ASM", "C", "C++", "Rust"],
        web_and_app: vec!["TS", "JS", "Python", "C#", "Java", "PHP", "HTML", "CSS"],
        tools:       vec!["Linux", "Nginx", "Bun", "Node", "Astro", "Svelte", "TailwindCSS"],
    },
    projects: vec![
        // Work in progress...
    ],
};

```
