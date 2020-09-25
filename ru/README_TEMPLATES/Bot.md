<p align="center"><a href="" rel="noopener">  </a><img width="200px" height="200px" src="https://i.imgur.com/FxL5qM0.jpg" alt="Логотип бота"></p>

<h3 align="center">Имя бота</h3>

<div align="center">
</div>

[]()![Статус](https://img.shields.io/badge/status-active-success.svg)




---

<p align="center">🤖 Несколько строк, описывающих, что делает ваш бот.<br></p>

## 📝 Содержание

- [О боте](#about)
- [Демо/Работа](#demo)
- [Как это устроено](#working)
- [Применение](#usage)
- [Начало работы](#getting_started)
- [Развертывание собственного бота](#deployment)
- [Построен с использованием](#built_using)
- [To Do](../TODO.md)
- [Участие](../CONTRIBUTING.md)
- [Авторы](#authors)
- [Благодарности](#acknowledgement)

## 🧐 <a name="about">О боте</a>

Напишите примерно 1-2 абзаца, описывающих назначение вашего бота.

## 🎥 Демо / Работа<a name="demo"></a>

![За работой](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 Как это работает<a name="working"></a>

Бот сначала извлекает слово из комментария, а затем извлекает определения слова, часть речи, пример и источник из Oxford Dictionary API.

Если этого слова нет в Оксфордском словаре, Oxford API возвращает ответ 404, после чего бот пытается получить результаты из API Urban Dictionary.

Бот использует Pushshift API для получения комментариев, модуль PRAW для ответа на комментарии и Heroku в качестве сервера.

Весь бот написан на Python 3.6.

## 🎈 Использование<a name="usage"></a>

Чтобы использовать бот, введите:

```
!dict word
```

Первая часть, т.е. "!dict", **не** чувствительна к регистру.

Затем бот предоставит вам определение слова в Оксфордском словаре (или Urban Dictionary, если слово не существует в Оксфордском словаре) в качестве ответа на комментарий.

### Пример:

> !dict что такое любовь

**Определение:**

Детка, не делай мне больно ~ Не делай мне больно ~ больше.

**Пример:**

Чувак1: Бро, что такое любовь? Чувак2: Детка, не делай мне больно, не больно мне больше! Чувай1: Чего?

**Источник:** https://www.urbandictionary.com/define.php?term=what%20is%20love.

---

<sup>Бип-буп. Я бот. Если есть какие-либо вопросы, свяжитесь с моим <a href="https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot">Мастером</a></sup>

<sup>Хотите сделать похожего бота на Reddit? Проверьте: <a href="https://github.com/kylelobo/Reddit-Bot">GitHub</a></sup>

## 🏁 Начало работы<a name="getting_started"></a>

Эти инструкции позволят вам запустить копию проекта на локальном компьютере в целях разработки и тестирования. К ак развернуть проект в действующей системе описано в разделе [Развертывание](#deployment).

### Предпосылки

Что нужно для установки программного обеспечения и как их установить.

```
Give examples
```

### Установка

Пошаговая серия примеров, рассказывающих, как запустить среду разработки.

Скажите, какой будет шаг

```
Give the example
```

И повторить

```
until finished
```

Закончите примером получения некоторых данных из системы или использования их для небольшой демонстрации.

## 🚀 Развертывание собственного бота<a name="deployment"></a>

Чтобы увидеть пример проекта по развертыванию бота, просмотрите мою собственную конфигурацию:

- **Heroku** : https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ Построен с использованием<a name="built_using"></a>

- [PRAW](https://praw.readthedocs.io/en/latest/) — Python Reddit API Wrapper
- [Heroku](https://www.heroku.com/) —хостинговая платформа SaaS

## ✍️ Авторы<a name="authors"></a>

- [@kylelobo](https://github.com/kylelobo) — Идея и начальная работа

Список [участников](https://github.com/kylelobo/The-Documentation-Compendium/contributors), работавших в этом проекте.

## 🎉 Благодарности<a name="acknowledgement"></a>

- Спасибо всем, чей код использовался
- Вдохновение
- Ссылки
