# Esp32c3 setup for rust

### Install esp up
``` sh 
cargo install espup --locked
```

### Install esp tools
``` sh
espup install
```

### Install esp generate for creating a project from template
``` sh
cargo install esp-generate --locked
```

### Generate a project with esp-generate
``` sh
esp-generate --chip esp32s3 -o stack-smashing-protection -o esp-backtrace -o esp [-o editor:zed] <project>
```

#### *Or with cargo generate*
``` sh
cargo generate esp-rs/esp-idf-template cargo
```

## Then run env script where it was generated
``` sh
. ~/export-esp.sh
```
