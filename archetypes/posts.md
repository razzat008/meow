+++
date = '{{ .Date }}'
draft = false
title = '{{ replace .File.ContentBaseName `-` ` ` | title }}'
toc = false
description = ''
slug = '{{ .File.ContentBaseName }}'
tags = []
+++
