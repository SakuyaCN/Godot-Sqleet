# Godot-Sqleet 

SQLite Encryption lib

Fork from https://github.com/2shady4u/godot-sqlite/tree/godot-sqleet

This is a compiled library, you don’t need to compile it yourself, you can use it directly

**How to install:**

See https://github.com/2shady4u/godot-sqlite README.md

Download 
```
/android File Folder
```
and replace 
```
/demo/addons/godot-sqlite/bin/android/
```

Example usage:

```
var db = SQLite.new()
db.path = db_name
if OS.get_name() == "Android":
	db.encryption = true
	db.password = "111"
...
...
db.open_db()
```

Thanks > https://github.com/2shady4u for his contribution
