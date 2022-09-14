me in a nutshell: When you make discord bot, I will make platform that improved than discord and open source  
```rs

struct misilestruct {
  site: String,
  feel: u8
}

trait misilemethods {
  fn handling_feel(feel: u8) -> u8;
}

impl misilemethods for misilestruct {
   fn handling_feel(&self) {
    return random(feel-50, feel+1);
  }
}

fn main() {
   let misile = misilestruct {
    site: "https://misilelaboratory.xyz",
    feel: 255
  };
  loop {
    misile.handling_feel();
    sleepday();
  };
}

```
