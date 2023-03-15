# pklalitjha
  <http://spring-webservice-2-step-by-step.blogspot.com>
  <nospam+sylentprayer@gmail.com>

## <a href='./components/Elasticsearch Indexing/readme.md'><img src='./components/Elasticsearch Indexing/logo.jpg' width='40' height='40'> Elasticsearch Indexing</a>
 :warning: Compatibility not known

Data ingesting in Elasticsearch cluster. Combined with tMustache to do complex transformation of data into nested JSON.
<img src='./components/Elasticsearch Indexing/sample.jpg'>

## <a href='./components/tMustache/readme.md'><img src='./components/tMustache/logo.jpg' width='40' height='40'> tMustache</a>
 :warning: Compatibility not known

This component is for using Mustache template in Talend flow. This takes Mustache template (content as String) as argument  and uses rows as parameters for template execution.

This applies template on data in rows and outputs template output and all data in row, to continue the flow. Template can be any valid Mustache template, so it can transform rows into HTML, JSON or any other format.

Column names in schema must be same as variables in template.

Mustache template for producing JSON:
{
"id":{{id}},
"key":"{{key1}}",
"child":{
"key":"{{key2}}",
"grandchild":"{{key3}}",
"array":[{{id}},"{{key4}}","{{key5}}"]
}
}
And, schema has id, key1, key2, key3, key4 and key5 columns, all randomly generated.

This produced JSON as:
{\t"id":96,\t"key":"ZvEWMb",\t"child":{\t"key":"eXIwbJ",\t"grandchild":"7DvrDc",\t"array":[96,"Kukaxs","Ox1sWo"]\t}}

Can write complex Mustache template for complicated output.

Sample usecase can be:
1. Elegant email body.
2. Rich HTML/JSON or other textual format output.
.....
See sample jobs and and tutorial for more detail.
<img src='./components/tMustache/sample.jpg'>
