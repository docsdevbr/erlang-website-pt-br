---
# SPDX-FileCopyrightText: 1996-2026 Ericsson AB. All rights reserved.
#
# SPDX-License-Identifier: Apache-2.0
# Documentation licensed under the Apache License, Version 2.0.
# The original work was translated from English into Brazilian Portuguese.
# https://github.com/docsdevbr/erlang-website-pt-br/blob/-/LICENSES/Apache-2.0.txt

source_url: https://github.com/erlang/otp/blob/maint-28/system/doc/installation_guide/installation_guide.md
revision: a87183f1eb847119b6ecc83054bf13c26b8ccfaa
status: ready
---

# Introdução

Esta seção descreve como compilar, instalar e aplicar patches ao Erlang/OTP no
UNIX e no Windows.

- **[Compilando e instalando o Erlang/OTP](INSTALL.md)** - Descreve como
  compilar e instalar o Erlang/OTP em qualquer plataforma UNIX, ou seja, Linux,
  macOS, qualquer BSD, Solaris e assim por diante.
- **[Compilação cruzada do Erlang/OTP](INSTALL-CROSS.md)** - Descreve como usar
  um [compilador cruzado] para compilar o Erlang/OTP em qualquer plataforma
  UNIX.
- **[Compilando o Erlang/OTP no Windows](INSTALL-WIN32.md)** - Descreve como
  compilar o Erlang/OTP para o Windows 10 usando o WSL.

Existem também vários outros guias para outros sistemas operacionais localizados
na pasta [Erlang/OTP HOWTO](https://github.com/erlang/otp/blob/master/HOWTO/).

> #### Nota {: .info }
>
> Dependendo do sistema operacional e da sua familiaridade com o uso do GNU
> configure/make, pode ser difícil compilar o Erlang/OTP.
> Portanto, recomenda-se primeiro acessar <https://erlang.org/downloads> e
> verificar se uma versão pré-compilada do Erlang/OTP pode ser usada.

Se o objetivo de compilar o Erlang/OTP é contribuir para o seu desenvolvimento,
recomenda-se consultar os documentos
[Contribuindo para o Erlang/OTP](https://github.com/erlang/otp/blob/master/CONTRIBUTING.md)
e
[Desenvolvendo o Erlang/OTP](https://github.com/erlang/otp/blob/master/HOWTO/DEVELOPMENT.md).

[compilador cruzado]: https://en.wikipedia.org/wiki/Cross_compiler
