+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
slug = '{{ .File | lower }}'
type = 'collections'
layout = 'post'
+++
