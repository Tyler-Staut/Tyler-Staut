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
        ("- ā” Quick bio:".to_string(), 
            "I am currently a cloud security engineer working to become a certified penetration tester".to_string()),

        ("- š­ Iām currently working on".to_string(), 
            "Not taking down production servers š".to_string()),
            
        ("- š± Iām currently learning".to_string(), 
            "How to become a better penetration tester in the cloud".to_string()),

        ("- š» Iām looking to collaborate on".to_string(),
            "Any fun and interesting project".to_string()),

        ("- š¤ Iām looking for help with".to_string(), 
            "Anything related to what I am currently learning ".to_string()),

        ("- š® I'm currently playing".to_string(), 
            "Flight Simulator āļø".to_string()),

        ("- šļø I'm currently watching".to_string(), 
            "Too much Formula 1".to_string()),

        ("- š¬ Ask me about".to_string(), 
            "Cloud Security | Red Teaming | Competitions".to_string()),

        ("- š„ Blog:".to_string(), 
            "https://blog.tyler-staut.cloud/".to_string()),
    ])
}
```
