# To-Do SaaS App (React)

Basit bir SaaS tarzı To-Do List uygulaması.

- React ile yapıldı.
- Backend veya veritabanı yok.
- Tüm görevler tarayıcının `localStorage` alanında saklanır.
- Görev ekleme, tamamlandı olarak işaretleme, silme ve filtreleme özellikleri vardır.
- Responsive, sade ve kullanıcı dostu arayüz.

## Kurulum ve Çalıştırma

1. React projenize `ToDoSaaSApp.jsx` dosyasını ekleyin.
2. `App.js` ya da ana dosyanızda import edin ve kullanın:

```jsx
import React from 'react';
import ToDoSaaSApp from './ToDoSaaSApp';

function App() {
  return (
    <div>
      <ToDoSaaSApp />
    </div>
  );
}

export default App;
