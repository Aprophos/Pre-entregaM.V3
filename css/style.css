*, *::before, *::after {
  /* outline: 1px solid red; */
  margin: 0;
  padding: 0;
  list-style: none;
  box-sizing: border-box;
}
:root {
  --color-red: #D90429;
  --color-red-light: #EF233C;
  --color-gray: #8D99Ae;
  --color-gray-dark: #353739;
  --color-gray-light: #EDF2F4;
  --color-black-light: #2B2D42;
  --color-white: #FFFFFF;
  --color-blue: #0866ff;
  --color-orange: #d93a00;
  --font-primary: "Poppins", sans-serif;
}
html {
  scroll-behavior: smooth;
}
body {
  font-family: var(--font-primary);
  position: relative;
  font-size: 1rem;
  background-color: var(--color-gray-light);
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-rendering: optimizeLegibility;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
/* Header */
.header {
  background-color: var(--color-black-light);
}
.header-container {
  display: flex;
  width: 100%;
  max-width: 1200px;
  margin: auto;
  padding: 0 1rem;
}
.header-market {
  display: flex;
  width: 50%;
  justify-content: flex-start;
  align-items: center;
  gap: 1rem;
}
.header-market-logo {
  width: 4rem;
}
.header-market-title {
  font: normal 700 2rem/1.2 var(--font-primary);
  color: var(--color-white);
  letter-spacing: 1px;
}
/* Menu su Encabezado */
.header-menu {
  display: flex;
  width: 50%;
}
.header-menu-list{
  display: flex;
  justify-content: end;
  width: 100%;
  align-items: center;
  gap: 1rem;
}
.header-menu-list-item-link {
  color: var(--color-white);
  text-decoration: none;
  padding: 1rem;
  display: block;
  border-radius: 4px;
  transition: background 0.3s ease;
}
.header-menu-list-item-link:hover {
  background-color: var(--color-red-light);
  color: var(--color-white);
  transition: background 0.3s ease;
}
.header-menu-list-item-link.active {
  background-color: var(--color-red-light);
  color: var(--color-white);
}

/* Menu Hamburguesa */
.menu-btn {
  display: none;
	width: 30px;
	height: 30px;
	position: fixed;
	z-index:2;
	overflow: hidden;
  top: 1rem;
  right: 1rem;
}

.menu-btn .bar {
	width: 30px;
	height: 4px;
	position: absolute;
	top: 50%;
	left: 50%;
  border-radius: 4px;
	transform: translate(-50%, -50%);
	background-color: var(--color-white);
	transition: all 0.3s ease-in-out;
}

.menu-btn .bar:nth-of-type(2) {
	top: calc(50% - 9px);
}
.menu-btn .bar:nth-of-type(3) {
	top: calc(50% + 9px);
}


.menu-btn.active .bar:nth-of-type(1) {
  display: none;
}
.menu-btn.active .bar:nth-of-type(2) {
  top: 50%;
  transform: translate(-50%, 0%) rotate(45deg);
}
.menu-btn.active .bar:nth-of-type(3) {
  top: 50%;
  transform: translate(-50%, 0%) rotate(-45deg);
}


/* Contenedor Principal */
.main-container {
  width: 100%;
  max-width: 1200px;
  margin: 1rem auto 3rem;
  padding: 0 1rem;
}
/* BANNER */
.banner-container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.banner-img {
  width: 100%;
  border-radius: 0.5rem;
}

/* DESCRIPCION */
.descripcion {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-bottom: 2rem;
}
.descripcion-titulo {
  font: normal 700 2rem/1.2 var(--font-primary);
  color: var(--color-black-light);
  margin: 1rem auto;
}
.descripcion-subtitulo {
  font: normal 400 1.5rem/1.2 var(--font-primary);
  color: var(--color-black-light);
  margin: 1rem auto;
}

/* CONTENEDOR MAIN PRODUCTOS*/
.productos-main {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  gap: 1rem;
  position: relative;
  margin: 0 auto;
}
/* INICIO CATEGORY*/
.productos-category {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-direction: column;
  width: 100%;
  max-width: 210px;
  border-radius: 0.5rem;
  background-color: var(--color-white);
  padding: 1rem;
  position: sticky;
  top: 1rem;
  border: 1px solid rgba(0, 0, 0, .1);
}
.productos-category-title {
  display: block;
  width: 100%;
}
.productos-category-sales {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  width: 100%;
  gap: 1rem;
  flex-wrap: wrap;
}
.productos-category-item {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-direction: column;
  width: 100%;
  gap: 1rem;
}
.productos-category-nav {
  width: 100%;
  display: flex;
  flex-direction: column;
}
.productos-category-nav-item {
  width: 100%;
  padding: 1rem 0.5rem;
  border-bottom: 1px solid rgba(0, 0, 0, .1);
  transition: all 0.3s ease;
}
.productos-category-nav-item:last-child {
  border-bottom: none;
}
.productos-category-nav-item:hover {
  cursor: pointer;
  background-color: var(--color-gray-light);
  border-radius: 0.5rem;
  position: relative;
  transition: all 0.3s ease;
}
.productos-category-nav-item:hover::after {
  content: "→";
  position: absolute;
  font-size: 1.5rem;
  color: var(--color-black-light);
  width: 1rem;
  height: 1rem;
  right: 1rem;
}
.productos-category-nav-item__link {
  width: 100%;
  text-decoration: none;
  font: normal 400 1rem/1.2 var(--font-primary);
  color: var(--color-black-light);
}
/* Inicio Productos*/

.productos-container {
  width: 100%;
  max-width: 1200px;
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1rem;
  flex-wrap: wrap;
  margin-bottom: 10rem;
}
.productos {
  width: 240px;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: column;
  margin-bottom: 2rem;
  transition: all 0.3s ease;
  border: 1px solid transparent;
  border-radius: 0.5rem;
  background-color: var(--color-white);
  overflow: hidden;
  cursor: default;
  transition: all 400ms;
}
.productos-category-sales.productos-wrap {
  justify-content: flex-start;
  align-items: flex-start;
}
.productos-category-sales.productos-wrap .productos {
  width: 215px;
}
.productos:hover {
  border: 1px solid var(--color-gray);
  transition: all 0.3s ease;
  box-shadow: 0px 0px 10px 5px rgb(0 0 0 / 10%);
  transform: translateY(-2%);
}
.productos-body {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: column;
  padding: 1rem;
}
.productos-img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 8px 8px 0 0;
}

.productos-desc {
  font: normal 400 1rem/1.2 var(--font-primary);
  color: var(--color-black-light);
  margin-bottom: 0.5rem;
  text-align: center;
  min-height: 60px;
}

.productos-marca {
  text-align: center;
  width: 50%;
  position: relative;
  font: normal 700 0.75rem/1.2 var(--font-primary);
  color: var(--color-black-light);
  margin-bottom: 1rem;
}
.productos-marca::before {
  content: '';
  display: block;
  border-top: 1px solid #e9e9e9;
  width: 100%;
  margin: 5px 0;
}
.productos-precio {
  font: normal 700 1.25rem/1.2 var(--font-primary);
  color: var(--color-black-light);
  margin-bottom: 1rem;
}
.productos-btn {
  font: normal 700 1.25rem/1.2 var(--font-primary);
  padding: 0.5rem 1rem;
  background-color: var(--color-red);
  color: var(--color-white);
  border-radius: 0.25rem;
  border: none;
  outline: none;
  transition: background 0.3s ease;
}
.productos-btn:hover {
  background-color: var(--color-red-light);
  color: var(--color-white);
  transition: background 0.3s ease;
  cursor: pointer;
}

/*Sección Productos*/
.productos-title{
  text-align: center;
  margin: 2rem auto 3rem;
}

/*Footer*/
.footer{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background-color: var(--color-black-light);
  color: var(--color-white);
  padding: 1rem 0;
  text-align:center;
  width: 100%;
}
.footer__titulo {
  font: normal 700 1.25rem/1.2 var(--font-primary);
  padding: 0 1rem;
  margin: 1rem auto;
}
.footer-sociales {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 350px;
  gap: 1rem;
  border-radius: 4px;
  margin-bottom: 2rem;
}

.footer-sociales__link {
  font-size: 3rem;
  padding: 1rem;
}

.footer__copyright {
  font: normal 300 0.85rem/1.2 var(--font-primary);
  padding: 0 1rem;
}
.fa-instagram {
  color: var(--color-red-light);
  border-radius: 8px;
}
.fa-facebook {
  color: var(--color-blue);
  border-radius: 50%;
}
.fa-square-reddit {
  color: var(--color-orange);
  border-radius: 4px;
}
.fa-instagram,
.fa-facebook,
.fa-square-reddit {
  transition: all 0.3s ease;
}
.fa-instagram:hover,
.fa-facebook:hover,
.fa-square-reddit:hover {
  transition: all 0.3s ease;
  box-shadow: 0px 0px 10px 5px rgb(0 0 0 / 10%);
}

/* Páginas */
.nosotros {
  width: 100%;
  max-width: 991px;
  margin: auto;
}
.nosotros__title {
  font: normal 700 3rem/1.2 var(--font-primary);
  text-align: center;
  background-color: var(--color-red-light);
  color: var(--color-white);
  padding: 0.5rem 1rem;
  border-radius: 0.25rem;
}
.nosotros__subtitle {
  font: normal 700 2rem/1.2 var(--font-primary);
  text-align: center;
  margin-bottom: 1rem;
  color: var(--color-gray-dark);
}
.nosotros__desc {
  font: normal 400 1rem/1.2 var(--font-primary);
  text-align: center;
  margin-bottom: 2rem;
  color: var(--color-gray-dark);
}

.form-container {
  width: 100%;
  max-width: 575px;
  margin: 2rem auto;
}
.form-body {
  width: 100%;
  max-width: 100%;
}
.form-body__title {
  font: normal 700 3rem/1.2 var(--font-primary);
  text-align: center;
  color: var(--color-black-light);
  padding: 0.5rem 1rem;
  border-radius: 0.25rem;
}

.form-body__input,
.form-body__textarea,
.form-body__submit {
  width: 100%;
  font: normal 400 1rem/1.2 var(--font-primary);
  padding: 0.8rem 1rem;
  border: 1px solid var(--color-gray);
  border-radius: 4px;
  margin-bottom: 1rem;
}
.form-body__input:focus,
.form-body__textarea:focus {
  border: 1px solid var(--color-red-light)
}
.form-body__submit {
  width: 100%;
  font: normal 400 1.5rem/1.2 var(--font-primary);
  text-align: center;
  background-color: var(--color-red-light);
  color: var(--color-white);
  border: none;
  outline: 0;
  border-radius: 4px;
  transition: all 0.3s ease;
  padding: 1rem 0;
}
.form-body__submit:hover {
  transition: all 0.3s ease;
  background-color: var(--color-red);
  cursor: pointer;
}
.serviciostitulo {
  display: flex;
  justify-content: center;
  border-radius: 7px;
  background-color: red;
  color: white;
}

/* Media Query */
@media (max-width: 991px){
  .main-container {
    margin-top:5rem;
  }
  .header-container {
    position: fixed;
    z-index: 1;
    background-color: var(--color-black-light);
  }
  .menu-btn, .header-menu-list{
    display: block;
  }
  .header-market-logo{
    width: 3rem;
  }
  .menu-btn:hover {
    cursor: pointer;
  }
  .header-market-title{
    font-size: 1.5rem;
  }
  .header-market{
    width: 100%;
  }
  .header-menu-list{
    position: fixed;
    top: 61px;
    left: -100%;
    width: 100%;
    height: 280px;
    padding: 15px;
    background-color: var(--color-black-light);
    transform: translateX(0);
    transition: transform 0.5s;
    z-index: 1;
  }
  .header-menu-list.active {
    transform: translateX(100%);
    z-index: 1;
  }
  .descripcion-titulo {
    font-size: 1.5rem;
  }
  .descripcion-subtitulo {
    font-size: 1rem;
    text-align: center;
  }
}

@media (max-width: 768px) {
  .menu-btn {
    right: 2rem;
  }
  .productos-main {
    flex-direction: column;
  }
  .productos-category {
    max-width: 100%;
    border: none;
    border: 1px solid rgba(0, 0, 0, .1);
    top: 4.5rem;
    z-index: 2;
  }
  .productos-category-sales.productos-wrap .productos {
    width: 100%;
  }
  .productos-category-nav-item {
    border: none;
  }
  .productos-category-nav {
    flex-direction: row;
  }
  .productos-category-nav-item:hover .productos-category-nav-item__link {
    text-decoration: underline;
  }
  .productos-category-nav-item:hover::after {
    content: "";
  }
  .productos {
    width: 100%;
    max-width: calc(50% - 0.5rem);
  }
  .productos-desc {
    min-height: 2.5rem
  }
  .productos-btn {
    font-size: 1rem;
  }
}
@media (max-width: 575px) {
  .productos-category-nav-item__link {
    font-size: 0.8rem;
    font-weight: 600;
  }
  .header-market-title {
    font-size: 1.25rem;
    padding: 0.25rem 0;
  }
}