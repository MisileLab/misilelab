[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine)

```rs

struct misilestruct {
  site: String,
  feel: u8
}

trait misilemethods {
  fn handling_feel(feel: u8) -> u8;
}

impl misilemethods for misile {
   fn handling_feel(&self) {
    return random(feel-50, feel+1);
  }
}

fn main() {
  while true {
    let misile = misilestruct {
      site: "https://misilelaboratory.xyz",
      feel: 255
    };
    misile.handling_feel();
    sleepday();
  };
}

```
