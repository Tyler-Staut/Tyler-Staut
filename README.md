# Hello World

`git config --global user.name "Tyler Staut"`

# About Me (Written in Rust :crab:)

```Rust
use std::collections::HashMap;

fn main() {
    for (key, val) in Bio().iter() {
        println!("{} {}", key, val);
    }
}

fn Bio() -> HashMap<String, String> {
    HashMap::from([
        ("- ⚡ Quick bio:".to_string(), 
            "I am currently a cloud security engineer working to become a certified penetration tester".to_string()),

        ("- 🔭 I’m currently working on".to_string(), 
            "Not taking down production servers 😅".to_string()),
            
        ("- 🌱 I’m currently learning".to_string(), 
            "How to become a better penetration tester in the cloud".to_string()),

        ("- 💻 I’m looking to collaborate on".to_string(),
            "Any fun and interesting project".to_string()),

        ("- 🤔 I’m looking for help with".to_string(), 
            "Anything related to what I am currently learning ".to_string()),

        ("- 🎮 I'm currently playing".to_string(), 
            "Flight Simulator ✈️".to_string()),

        ("- 🏎️ I'm currently watching".to_string(), 
            "Too much Formula 1".to_string()),

        ("- 💬 Ask me about".to_string(), 
            "Cloud Security | Red Teaming | Competitions".to_string()),

        ("- 🔥 Blog:".to_string(), 
            "https://blog.tyler-staut.cloud/".to_string()),
    ])
}
```
