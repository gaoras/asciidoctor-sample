output_dir = dist
file = index.adoc

pdf:	$(file)
	asciidoctor-pdf -D $(output_dir) $(file)

html:	$(file)
	asciidoctor -D $(output_dir) $(file)
