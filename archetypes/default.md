+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
slug: {{ substr .File.UniqueID 0 7 }}
+++
