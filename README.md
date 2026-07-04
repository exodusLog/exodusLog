### No a big of coding but doing it makes more sense then going out and touch some grass...
***
_Loves the backend cause it gives me clarity._
> Not a big of "Will fix it later"

`Just like rust, I have the same ownership rule, I can have multiple immutable refs for the same value but only one mutable ref`

```rs
#[derive(Debug)]
struct Me {
  name: String,
  profecient: String,
  projects: u32,
  domain: String,
  active: bool,
}

fn main(){
  let about = Me {
  name: String::from("Exodus"),
  profecient: String::from("ts"),
  projects: 6,
  domain: String::from("backend"),
  active: true,
  }

  println!("This is a breif about me but in rust: {:#?}",about)
}
```
