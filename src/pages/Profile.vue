<template>
  <div class="row">
    <div class="col-md-8">
      <edit-profile-form :model="model">
      </edit-profile-form>
    </div>
    <div class="col-md-4">
      <user-card :user="user"></user-card>
    </div>
  </div>
</template>
<script>
  import EditProfileForm from './Profile/EditProfileForm';
  import UserCard from './Profile/UserCard'
  export default {
    components: {
      EditProfileForm,
      UserCard
    },
    data() {
      return {
        model: {
          company: 'Banco Original.',
          email: 'pedro.francyscc@email.com',
          username: 'nkiambi',
          firstName: 'Pedro Francisco',
          lastName: 'Nkiambi',
          address: 'Salvador Allende 971 - BL 03- Ap 707 - Barra ',
          city: 'Rio de Janeiro',
          country: 'Brasil',
          about: 'Engenheiro de Software.'
        },
        user: {
          fullName: 'Pedro Francisco Nkiambi',
          title: 'Ceo/Co-Founder',
          description: `Do not be scared of the truth because we need to restart the human foundation in truth And I love you like Kanye loves Kanye I love Rick Owens’ bed design but the back is...`,
        }
      }
    }
  }
</script>
<style>
</style>
