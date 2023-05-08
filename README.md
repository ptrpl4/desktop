<h1 align="center">
  <img src="./src-tauri/icons/128x128.png" alt="OneKeePass" width="128" />
  <br>
  <div>OneKeePass</div>
</h1>

**OneKeePass** is a cross-platform,open source and secure password manager. It supports the KeePass-compatible database (Kdbx 4.x). It stores and manages all your passwords and other sensitive information in a single encrypted file that can be stored in any location, including private and public cloud solutions. The database is locked with a master key. 

All created database files are encrypted using the best and most secure encryption algorithms currently known (AES-256, ChaCha20).

<h1 align="center">
  <img src="./screenshots/entrycategory-type-allentries.jpg" alt=""  />
  <br>
</h1>


## Features
- Simple and Modern UI
- Entries are grouped as Types or Categories or the standard Group tree
- Custom entry type with any set of fields can be created as template and used to create entries
- Any number of custom fields can be added
- Custom fields can be organized as sections
- Any number of databases can be created and used
- Fully offline 

## Todo
- [ ] Upload attachments to an entry 
- [ ] Browser extension and integration
- [ ] TOTP storage and generation 
- [ ] Autotype feature
- [ ] Merge changed entries
- [ ] Synchronize the database between the devices 
- [ ] Multi-language support
- [ ] Support YubiKey 
- [ ] Integrate with biometrics (fingerprint)


## Installation and Quick start

You can start using OneKeePass on your Windows, macOS, or Linux computer using the latest pre-compiled binaries from the **[downloads page](https://github.com/OneKeePass/desktop/releases)**

**If you encounter the error message `"OneKeePass" is damaged and can't be opened. You should move it to the Trash`. while installing software on macOS, it may be due to security settings restrictions in macOS. To solve this problem, please try the following command in Terminal:**

```bash
sudo xattr -r -d com.apple.quarantine /YOUR_PATH/OneKeePass.app
```

**FAQ** can be found [here](./docs/FAQ.md)


## How to build

OneKeePass is developed primarily using the ClojureScript and Rust programming languages and is built with - [Tauri](https://tauri.app/),[React](https://react.dev/),[MUI](https://mui.com/) and many Rust crates

To build your own binary, please follow the instructions [here](BUILD.md)

 
## How to Contribute
The CONTRIBUTING document and other guidelines for code contributions are not yet ready. Till that time, please feel free to::
- [Report bugs, suggest new features](https://github.com/OneKeePass/desktop/issues)

## License
This project is licensed under the GPLv3.