vue-snippet

File -> Preperences -> User snippet -> Vue
{
  // Place your snippets for vue here. Each snippet is defined under a snippet name and has a prefix, body and
  // description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
  // $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the
  // same ids are connected.
  // Example:
  // "Print to console": {
  // 	"prefix": "log",
  // 	"body": [
  // 		"console.log('$1');",
  // 		"$2"
  // 	],
  // 	"description": "Log output to console"
  // }

  "Generate Basic Vue Code": {
    "prefix": "vue-start",
    "body": [
      "<template>\n\t<div></div>\n</template>\n<script>\nexport default {\n\tname: '',\n\tcomponents: {},\n\tcreated() {},\n\tbeforeMount() {},\n\tmounted() {},\n\tbeforeUpdate() {},\n\tupdated() {},\n\tbeforeUnmount() {},\n\tunmounted() {},\n\tmethods: {}\n};\n</script>"
    ],
    "description": "Generate Basic Vue Code"
  }
}
