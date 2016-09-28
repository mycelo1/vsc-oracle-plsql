# ORACLE-PLSQL

**Oracle PL/SQL syntax highlighting**

This is a straight port from *Oracle PL/SQL TextMate bundle for Sublime Text 2/3* taken from [https://github.com/mulander/oracle.tmbundle](https://github.com/mulander/oracle.tmbundle) which has been released under *GPL-2.0* license. All merits should go to its author(s).

---

## Features

This extension provides solely the syntax highlighting specifically for Oracle's proprietary PL/SQL database programming code. It *does not* provide identifier navigation, code snippets, folding, templates, compiling or debug support. It also *does not* support interfacing with *SQL\*Plus* or database servers. Finally, other *Oracle Database* supported languages have not been implemented (e.g. *Java*).

Most of *Oracle's PL/SQL* keywords are being recognized, including types, classes, declarations, DDL, DML, and built-in functions and packages (UTL, DBMS, etc).

---

## How to Use

* On opening a PL/SQL program file, click *Select Language Mode* on the bottom/right of your status bar. Then choose **PL/SQL (Oracle)** or select *Configure File Association* to make this your permanent highlighter for this file type.

* Alternatively, open your *User Settings* (`settings.json` file), via the *Command Palette* (`ctrl+shift+p`), and paste the following lines. You may add or remove extensions as you please.

        "files.associations": {
            "*.sql": "oracle",
            "*.ddl": "oracle",
            "*.dml": "oracle",
            "*.pks": "oracle",
            "*.pkb": "oracle"
        }

---

## Source

[https://github.com/mycelo1/vsc-oracle-plsql](https://github.com/mycelo1/vsc-oracle-plsql)

---

## Bug Report

[Create a bug report](https://github.com/mycelo1/vsc-oracle-plsql/issues)

---

## Release Notes

### 1.0.0

Initial release.

### 1.0.1

* Clarified the file association instructions
