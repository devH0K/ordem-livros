<script>
  import { IconBooks, IconBrandFacebook, IconBrandInstagram, IconBrandYoutube, IconFriends, IconHome, IconRss, IconSquare1, IconSquare2, IconSquare3, IconUsers } from "@tabler/icons-svelte";
  import Menu from "./Menu.svelte";
  import MenuItem from "./MenuItem.svelte";
</script>
<aside class="flex flex-col gap-10 self-start border border-zinc-800 p-5 rounded-md w-72">
  <Menu titulo="Navegação">

    <MenuItem texto="Início" link="/">
      <IconHome size={20}/>
    </MenuItem>
    
    <MenuItem texto="Personagens" link="/">
      <IconFriends size={20}/>
    </MenuItem>
    
    <MenuItem texto="Autores" link="/autores">
      <IconUsers size={20}/>
    </MenuItem>
    
    <MenuItem texto="Séries" link="/">
      <IconBooks size={20}/>
    </MenuItem>

  </Menu>

  <Menu titulo="Principais Autores">
    
    <MenuItem texto="J.K Rowling" link="/autores/j-k-rowling">
      <IconSquare1 size={20}/>
    </MenuItem>
    
    <MenuItem texto="J.R.R. Tolkien" link="/autores/j-r-r-tolkien">
      <IconSquare2 size={20}/>
    </MenuItem>
    
    <MenuItem texto="George R.R. Martin" link="/autores/george-r-r-martin">
      <IconSquare3 size={20}/>
    </MenuItem>

  </Menu>

  <Menu titulo="Outras Categorias">
    
    <MenuItem texto="Últimas Notícias" link="/">
      <IconRss size={20}/>
    </MenuItem>
    
    <MenuItem texto="Séries Populares" link="/">
      <IconBooks size={20}/>
    </MenuItem>
    
    <MenuItem texto="Facebook" link="/">
      <IconBrandFacebook size={20}/>
    </MenuItem>
    
    <MenuItem texto="Instagram" link="/">
      <IconBrandInstagram size={20}/>
    </MenuItem>
    
    <MenuItem texto="Youtube" link="/">
      <IconBrandYoutube size={20}/>
    </MenuItem>
  
  </Menu>
</aside>