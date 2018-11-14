## Erlang HTTP Server

Instalación de Erlang

    $ sudo apt-get install erlang

Run al servidor 'inets':

    $ erl -s inets -eval 'inets:start(httpd,[{server_name,"NAME"},{document_root, "./public"},{server_root, "."},{port, 8000}
,{mime_types,[{"html","text/html"},{"htm","text/html"},{"js","text/javascript"},{"ico","image/x-icon"},{"css","text/css"},{"gif","image/gif"},{"jpg","image/jpeg"},{"jpeg
","image/jpeg"},{"png","image/png"}]}]).'

---

Fuentes:

+ https://gist.github.com/willurd/5720255
