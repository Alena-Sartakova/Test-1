<script setup lang="ts">

</script>

<template>
    <div class="container">
    <header>
        <div class="header">
            <nav class="header-nav">
                <label for="modal-toggle" class="open-modal-btn">
                    <img src="../img/Burger.png" alt="Меню" class="menu">
                </label>
                <input type="checkbox" id="modal-toggle" class="hidden">

<!-- Модальное окно -->
<div class="modal">
 <div class="modal-content">
 <label for="modal-toggle" class="close-button">
    <img src="../img/Burger-close.png">
 </label>
    <div class="menu-style">
        <a href="#">Главная</a>
        <a href="#">О нас</a>
        <a href="#">Контакты</a>
    </div>
 </div>
</div>
 
                <ul>
                    <li><a href="#"><img src="../img/Polygon 1.png"></a></li>
                    <li><a href="#"><img src="../img/Rectangle 6.png"></a></li>
                    <li><a href="#"><img src="../img/Ellipse 6.png"></a></li>
                </ul>
            </nav>
        </div>
    </header>
    <!-- Основной контент -->
    <main class="main">
      
        <div class="list-container">
            <ul class="hover-list">
            <li><a href="#">Главная</a></li>
            <li><a href="#">О нас</a></li>
            <li><a href="#">Контакты</a></li>
            </ul>
           </div>

        <div class="cards-container">
            <div class="card">
                <div class="card-content ">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>
           <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
            <div class="card">
                <div class="card-content">
                    <p class="text-multi-line">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    </p>
                </div>
            </div>            
        </div>

    </main>
    
    <footer>
        <div class="footer-container">
            <div class="footer-content">
                <h4>
                    Lorem ipsum?    
                </h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                </p>
            </div>
            <div class="footer-links">
                <a href="#">Главная</a>
                <a href="#">О нас</a>
                <a href="#">Контакты</a>
            </div>
            <div class="copyright">
                © 2025 Все права защищены
            </div>
        </div>
    </footer>
</div>
</template>

<style lang="scss" scoped>
/* Общие стили */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
}

.container {
    background-color: #D6BDFF; 
    border-radius: 10px; /* Скруглённые углы */
    box-shadow: 0 2px 5px rgba(0,0,0,0.2); /* Лёгкая тень */
    text-align: center; /* Выравнивание текста по центру */
    z-index: 1;
}

.main {
    display: flex;
}


   
/* Стили для header */
.header{
    padding: 20px ;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
.menu {
    display: none;
}
/* Скрываем чекбокс */
.hidden {
    display: none;
   }
   
   /* Стили для модального окна */
   .modal {
    display: none; /* Скрываем по умолчанию */
    position: fixed;
    z-index: 9999;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow-y: auto;
    background-color: rgba(0,0,0,0.4);
    padding: 5px;
    
   }
   
   /* Показываем модальное окно при checked чекбоксе */
   #modal-toggle:checked ~ .modal {
    display: flex;
    animation: fadeIn 0.3s;
   }
   
   .modal-content {
    background-color:#D6BDFF; 
    padding: 20px;
    border: 1px solid #888;
    width: 80%; 
    border-radius: 5px;
   }

   .close-button{
    float: right;
   }
  
   .close-button:hover,
   .close-button:focus {
    color: black;
   }
   .menu-style {
    display: flex;    ;
    flex-direction: column;
   }
   
   /* Анимация появления */
   @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
   }
   
.header-nav {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

.header-nav ul {
    list-style: none;
    display: flex;
    gap: 30px;
}

.header-nav a {
    text-decoration: none;
    color: #333;
    font-size: 16px;
    transition: color 0.3s;
}

.header-nav a:hover {
    color: #007bff;
}

/* Стили для card */

.cards-container {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.card {
    width: 160px;
    height: 128px;
    border-radius: 10px; 
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    overflow: hidden;
    margin: 20px;
    transition: box-shadow 0.3s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.card:hover {
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.card-content {
    padding: 15px;
    text-align: center;
}

.text-multi-line {
    overflow: hidden;
    display: -webkit-box;
    -webkit-line-clamp: 3; /* количество строк */
    -webkit-box-orient: vertical;
}

.card-content p {
    margin: 0 0 10px;
    color: #000;
    font-size: 14px;
}

.hide-partial-row {
    display: none;
}

.cards-container::before {
 content: "";
 flex: 1 0 100%;
 order: 999;
}

.cards-container > .card {
 order: -2;
}

/* Стили для list */

.list-container {
 width: 310px;
 box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.hover-list {
 list-style: none;
 padding: 0;
 margin: 0;
}

.hover-list li {
 position: relative;
 padding: 15px;
 margin-bottom: 5px;
 transition: all 0.3s;
}

.hover-list li:hover {
 transform: translateY(-2px);
 box-shadow: 0 4px 10px rgba(0,0,0,0.2);
 transition: box-shadow 0.3s;
 border-radius: 10px;
}

.hover-list a {
    text-decoration: none;
    margin: 0 0 10px;
    color: #000;
    font-size: 14px;
}

.hidden {
    display: none;
   }
   
   .click-area {
    cursor: pointer;
   }
   
   .hidden-content {
    max-height: 0;
    overflow: hidden;
    z-index: 999;
   }
   
   #toggle-block:checked ~ .hidden-content {
    max-height: 200px;
    padding: 20px;
   }
        

/* Стили для footer */

.footer {
    padding: 40px 0;
    
}

h4 {
   font-weight: bold; 
}
.footer-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
    text-align: left;
    
}

.footer-content {
    margin-bottom: 30px;
    font-size: 16px;
    line-height: 1.6;

}

.footer-links {
    display: flex;
    gap: 20px;
    justify-content: center;
}

.footer-links a {
    text-decoration: none;
    color: #333;
    transition: color 0.3s;
}

.footer-links a:hover {
    color: #007bff;
}

.copyright {
    text-align: center;
    margin-top: 20px;
    color: #999;
}


/* Дополнительные стили для медиа-запросов */
@media (max-width: 768px) {
    .header{
        background-color: #95D9FF;
        
    }
    .menu {
        display: block;
    }
 
    .header-nav {
        gap: 10px;
        padding: 15px 0;
    }

    .list-container {
        display: none;
     }

    .main{
        background-color: #bce6ff;
    }

    .header-nav{    
        display: flex;
        justify-content: space-between;
        padding: 10px 0;
    }
            .modal-content {
            width: 80%;
            height: 90%;
            top: 5px;
    
        }
        .footer-container{
            background-color: #95D9FF;
            }
}

@media (max-width: 320px){
.header {
  background-color: #ADFCC8;  
  
}

.main{
    background-color: #dbf9e6;  
}

.footer-container{
    background-color: #ADFCC8;  
}

.modal-content {
    width: 100%;
    height: 100%;
}
}


</style>
