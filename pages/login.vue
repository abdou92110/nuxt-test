<template>
<body>
  
  
  <form action="http://localhost:8080/api/users/login" method="POST">
    <div>
      <label for="email">Email</label>
      <input type="text" id="email" name="email"   placeholder="Identifiant" >
    </div>
    <div>
      <label for="password">Password</label>
      <input type="password" id="password" name="password" placeholder="Mot de passe">
    </div>
    <button type="submit">Envoyer</button>
  </form>

  <div >
    <a class="underlineHover" href="#">Mot de passe oublier</a>
   </div>
  
</body>
</template>