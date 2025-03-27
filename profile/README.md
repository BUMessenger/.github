# <img src="logo.svg" width="40" alt=""> **BUMessenger**  
#### *Мессенджер для разработчиков от разработчиков*  

---

<div align="center">  
  
[![Download Latest](https://img.shields.io/badge/Download-v1.0.0-red?style=for-the-badge&logo=github)](https://github.com/bumessenger/release/)  
[![Documentation](https://img.shields.io/badge/Docs-API%20Reference-black?style=for-the-badge)](https://github.com/bumessenger/docs)  
</div>  

---  

## ✨ **Особенности**  

| **Функция**               | **Описание** |
|---------------------------|-------------|
| **📝 Markdown** | Поддержка отправки форматированных в Markdown сообщений |
| **⮩ Умные треды**        | Ветвление обсуждений без потери контекста |
| **🎨 Тёмный режим**       | Черно-красная тема для приятной ночной работы |

```js
// Пример сообщения с кодом
function greetDev() {
  console.log("Привет, коллега! 👨‍💻");
  return <BUMessenger codeTheme="darcula" />;
}
```

---  

## 🖥 **Интерфейс**  

<div align="center">
| | |
|-|-|
| **Главный чат** | **Треды** |
| ![Чат](https://raw.githubusercontent.com/bumessenger/screenshots/main/chat-dark.png) | ![Треды](https://raw.githubusercontent.com/bumessenger/screenshots/main/threads-dark.png) |
</div>  

---  

## 📦 **Установка**  

### Через Release:  

```bash
curl -sL https://install.bumessenger.dev | bash
```

### Из исходников:  

```bash
git clone https://github.com/bumessenger/frontend.git
git clone https://github.com/bumessenger/backend.git
docker-compose up --build
```

---  

## 🔗 **Ресурсы**  

<div align="center">
[![Frontend](https://img.shields.io/badge/Frontend-React%20TS-black?style=flat-square&logo=react)](https://github.com/bumessenger/frontend)  
[![Backend](https://img.shields.io/badge/Backend-Node.js%20+%20Nest-red?style=flat-square&logo=nestjs)](https://github.com/bumessenger/backend)  
[![Documentation](https://img.shields.io/badge/Docs-GitBook-black?style=flat-square&logo=gitbook)](https://docs.bumessenger.dev)  
[![Releases](https://img.shields.io/badge/Downloads-Latest%20Build-red?style=flat-square&logo=docker)](https://github.com/bumessenger/release)  
</div>  

---  

<details>  
<summary>📜 Лицензия (MIT)</summary>  
  
```text  
Copyright 2024 BUMessenger Team
Разрешено свободное использование, модификация и распространение 
при условии сохранения копирайта и лицензионного уведомления.
```

</details>  
<div align="right">  
  
**✨ С любовью к коду**  

</div>  
### Ключевые элементы дизайна:  
1. **Черно-красная палитра** - через SVG-логотип и тематические badges
2. **Интерактивные элементы** - сворачиваемая лицензия, примеры кода
3. **Респонсив-таблицы** - для отображения скриншотов и фич
4. **Shields.io** - динамические бейджи для репозиториев
5. **Готовые команды** - curl/docker-compose для быстрого старта  

Для кастомизации:  
- Замените ссылки на реальные репозитории
- Обновите пути к скриншотам в `/screenshots/`
- Добавьте актуальную версию в бейдж Download
