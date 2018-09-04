# xon
XON formed as eXtendable Object Notion. Primarily a referenced based Data Object.
<*,{},[]>

Parts
  Head
  Body
  Child
  
Forms
  Pure
  XON-J based on JSON Format
  XON-X based on XML Format

Sample
Representation of XON in XON-J Format
With String Head
[
  "person",
  {
    "name":"Prakash Ayappan",
    "gender":"male"
  },
  [ ]
]

With Array Head
[
  ["Country","India"],
  {
    "population":"125 Crores",
    "Time Zone":"GMT+5:30"
  },
  []
]

With Object Head
[
  {
    "schema":{
      "rep":"individual",
      "provider":"schema.org"
    },
    "impl":{
      "groupId":"com.shrewon.xon",
      "artifactId":"xon-json-impl",
      "versionId":"1.0.0"
    },
    "usage":{}
  },
  {    
    "name":"Prakash Ayappan",
    "gender":"male"
  },
  []
]
