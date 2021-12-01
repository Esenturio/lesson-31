# hamburger
@media screen and (max-width: 992px) {
  .header__nav {
    display: flex;
    transform: translateX(200%);
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #63C6AE;
    transition: 0.5s;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    font-size: 3.625rem;
    color: white;
    padding: 2rem 0;
  }
}

.header__nav.is-active {
  transform: translate(20%);
}

.hamburger {
  padding: 0;
  display: none;
}
.hamburger * {
  padding: 0;
}
