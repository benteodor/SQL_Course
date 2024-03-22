# Intro

## storing data

1. memory

- memory will be cleared on every boot/program start

2. disk

- for persistance

## Disk storage

- plain text files
- structured text file
  - json
  - csv/tsv (Comma Separated Value/ Tab Separated Value)
  - xml
  - ini
  - svg (for images, xml file)
- binary file
  - data in binary format
  - images
  - audio
  - video

## Examples

- unicode.org

## plain text

```
Mary River
2024

Report

This year 2024 will be the begging of new project...

```

## better solutions

### Json document

```json
{
    "writer":{
        "firstname":"Mary River",
        "lastname":"River"
    },
    "year":2024,
    "type":"Report",
    "text":[
        "This year 2024 will be"
        "the begging of new project."
    ]
}
```

### XML documentation

```xml
<document>
    <writer>
        <firtname>Mary</firstname>
        <lastname>River</lastname>
    </writer>
    <year>2024</year>
    <type>Report</type>
    <text>
        This year 2024 will be the begging of new project...
    </text>
</document>

```

## Using text files as Data storage

### Json

```json
[
  {
    "firstname": "Mary",
    "lastname": "River",
    "age": 25
  },
  {
    "firstname": "Matt",
    "lastname": "Jones",
    "age": 30
  }
]
```

# XML

```xml
<persons>
    <person>
        <firstname>Mary</firstname>
        <lastname>River</lastname>
        <age>25</age>
    </person>
</person>
<persons>
    <person>
        <firstname>Matt</firstname>
        <lastname>Jones</lastname>
        <age>30</age>
    </person>
</person>
```

### CSV

```csv
firstname,lastname,age
Mary,River,25
Matt,Jones,30
```

OR

```csv
"firstname","lastname","age"
"Mary","River",25,
"Matt","Jones",30
```

[database]
driver=mysql
host=localhost
port=3306
databasename=persondb
[user]
username=zeke

```

```
