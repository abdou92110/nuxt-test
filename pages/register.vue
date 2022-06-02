<template>
<body>
  <form action="http://localhost:8080/api/users/register" method="POST">
    <div>
      <label for="email">Email</label>
      <input type="text" id="email" name="email"   placeholder="Identifiant" >
    </div>
     <div>
      <label for="username">Username</label>
      <input type="text"  id="username" name="username" placeholder="username">
    </div>
    <div>
      <label for="password">Password</label>
      <input type="password" id="password" name="password" placeholder="Mot de passe">
    </div>
    <div>
      <label for="bio">Bio</label>
      <input type="text"  id="bio" name="bio" placeholder="bio">
    </div>
    <button type="submit">Envoyer</button>
  </form>
  
</body>
</template>