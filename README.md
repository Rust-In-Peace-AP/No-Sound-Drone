# No Sound Drone :shushing_face:
  
  You should import it in the Cargo.toml as follow:  

  ```toml
  [dependencies]
  ap2024_rustinpeace_nosounddrone = { git = "https://github.com/Rust-In-Peace-AP/WindowsXP-Drone.git" }
  ```

  Then in the code like this: :mute:

  ```rust
  use ap2024_rustinpeace_nosounddrone;
  ...
  
  fn main(){
  
    let drone = ap2024_rustinpeace_nosounddrone::NoSoundDroneRIP::new(...);
  
  }
  
  
