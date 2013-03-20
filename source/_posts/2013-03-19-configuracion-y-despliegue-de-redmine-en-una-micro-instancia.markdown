---
layout: post
title: "Configuración y despliegue de Redmine en una micro instancia"
date: 2013-03-19 19:01
comments: true
categories:

- Rails
- Redmine
- Unicorn
- Apache
- Nginx
---

[Redmine](http://redmine.org) es una plataforma *open source* y gratuita
de gestión de proyectos **muy valorada** entre la comunidad Ruby y Rails.

Sus principales virtudes son una comunidad
[muy activa](https://github.com/redmine/redmine), un **enorme conjunto de
características** para gestión de proyectos software y un desarrollo
extensible basado en Rails.

<!-- more -->

Os invitamos a leer un artículo en el que se detalla el proceso de
configuración y despliegue de su versión más reciente en un servidor de
características reducidas (o micro instancia) usando **Apache** o **Nginx**
como *frontend* de procesos **Unicorn**.

Por supuesto, el proceso mencionado en este artículo es aplicable a cualquier
otro tipo de software basado en Rails y permite definir un
**entorno inicial** para la configuración y despliegue de aplicaciones: **[Setting up a cheap Redmine server using Unicorn and Apache](http://blog.davidanguita.name/2013/03/03/setting-up-a-cheap-redmine-server-using-unicorn-and-apache/).**
