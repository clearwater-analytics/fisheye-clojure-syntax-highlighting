# Fisheye/Crucible Clojure Syntax Highlighting

Basic Clojure syntax highlighting rules for Atlassian FishEye/Crucible.

References:
* https://confluence.atlassian.com/display/FISHKB/Defining+your+own+syntax+highlighting+in+Crucible+or+Fisheye
* https://confluence.atlassian.com/display/FISHKB/Configure+syntax+highlighting+for+non-standard+file+extensions

## How to Plug In

Step 1: Update the <FISHEYE_INST>/syntax/filename.map file with the following four lines:

```
"**/*.clj" clojure.def "Clojure"
"**/*.cljs" clojure.def
"**/*.cljc" clojure.def
"**/*.edn" clojure.def
```

Step 2: Put the clojure.def file in the <FISHEYE_INST>/syntax directory

Step 3: Restart Fisheye

## License
Copyright 2018 Clearwater Analytics LLC

This project is licensed under the MIT License - see [LICENSE.md](LICENSE.md) for details
