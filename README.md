# ORACLE-PLSQL

**Oracle PL/SQL syntax highlighting**

This is a fork of [mycelo's vsc extension](https://github.com/mycelo1/vsc-oracle-plsql) which is a straight port from [Oracle PL/SQL TextMate bundle for Sublime Text 2/3](https://github.com/mulander/oracle.tmbundle) which has been released under *GPL-2.0* license.

All merits should go to its original author(s).


All I did was change around some highlights and keywords.

---

## Features

This extension provides syntax highlighting for *Oracle*'s proprietary PL/SQL database programming language. It *does not* provide identifier navigation, code snippets, folding, completion, templates, compiling or debug support.

Most of *Oracle's PL/SQL* keywords are being recognized, including types, classes, declarations, exceptions, DML, built-in functions and default packages.

---

## How to Use

* On opening a PL/SQL program file, click *Select Language Mode* on the bottom/right of your status bar. Then choose **PL/SQL (Oracle)** or select *Configure File Association* to make this your permanent highlighter for this file type.

* Alternatively, open your *User Settings* (`settings.json` file), via the *Command Palette* (`ctrl+shift+p`), and paste the following lines. You may add or remove file types as you please.

        "files.associations": {
            "*.sql": "oracle",
            "*.ddl": "oracle",
            "*.dml": "oracle",
            "*.pks": "oracle",
            "*.pkb": "oracle"
        }

---

## Source

[https://github.com/Zsapi/vsc-oracle-plsql/](https://github.com/Zsapi/vsc-oracle-plsql/)
---

