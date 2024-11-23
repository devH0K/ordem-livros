<script>
  import Menu from "./Menu.svelte";
    import MenuItem from "./MenuItem.svelte";
</script>
<aside class="flex flex-col gap-10 self-start border border-zinc-800 p-5 rounded-md w-72">
  <Menu titulo="Navegação">
    <MenuItem texto="Início" link="/"/>
    <MenuItem texto="Personagens" link="/"/>
    <MenuItem texto="Autores" link="/autores"/>
    <MenuItem texto="Séries" link="/"/>
  </Menu>

  <Menu titulo="Principais Autores">
    <MenuItem texto="J.K Rowling" link="/"/>
    <MenuItem texto="J.R.R. Tolkien" link="/"/>
    <MenuItem texto="George R.R. Martin" link="/autores/george-martin"/>
  </Menu>

  <Menu titulo="Outras Categorias">
    <MenuItem texto="Últimas Notícias" link="/"/>
    <MenuItem texto="Séries Populares" link="/"/>
    <MenuItem texto="Facebook" link="/"/>
    <MenuItem texto="Instagram" link="/"/>
    <MenuItem texto="Youtube" link="/"/>
  </Menu>
</aside>