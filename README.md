# Minimal example for Kotlin native

I found this example in the [official documentation](https://kotlinlang.org/docs/native-gradle.html) when I was looking for a solution for building Kotlin or Java applications in the nix environment. The starting point of my search was [this post](https://discourse.nixos.org/t/problem-with-gradle-building-kotlin-native/7272) in the nixOS user forum.

Unfortunately, this example does not work properly with the `shell.nix` from the user forum. I expected that it would enable me with a shell to build the project with gradle.
