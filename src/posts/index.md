# Blog

Here are some things I wrote.

<!-- deno-fmt-ignore-start -->

{{range $doc := iterDocs "posts/" 0}}
- [{{$doc.Title}}]({{$doc.SlugPath}}) on {{$doc.Basename}}
{{end}}

<!-- deno-fmt-ignore-end -->
