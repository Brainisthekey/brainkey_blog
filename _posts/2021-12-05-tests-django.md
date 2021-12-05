---
layout: post
title: Django testing
date: 2021-12-05 10:40 +0800
last_modified_at: 2021-12-05 10:40 +0800
tags: [tests, tutorial, django]
toc:  true
---

When testing Django applications, I found an interesting combination of [Pytest fixtures](https://docs.pytest.org/en/latest/) and [FactoryBoy](https://factoryboy.readthedocs.io/en/stable/) to write tests that need database records.

{% gist c41c98b1678e9ec0bf0c2ecef1889d91 %}