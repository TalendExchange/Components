# sborion
  <nospam+sborions@gmail.com>

## <a href='./components/tLDAPAdOutput/readme.md'><img src='./components/tLDAPAdOutput/logo.jpg' width='40' height='40'> tLDAPAdOutput</a>
 :warning: Compatibility not known

It's just une little modification of standard tLDAPOutput Component for create/modify password in a Active Directory.

The difference is you can use a column of type byte[].

I have create another component for encrypte the password (and others transformation for a Active Directory): tLDAPPreparAuthAD

Warning : you must use a ssl connection for modify the unicodePwd
  


<img src='./components/tLDAPAdOutput/sample.jpg'>

## <a href='./components/tLDAPPreparAuthAD/readme.md'><img src='./components/tLDAPPreparAuthAD/logo.jpg' width='40' height='40'> tLDAPPreparAuthAD</a>
 :warning: Compatibility not known

Transform Data for a integration in a Microsoft Active Directory.

You can :

- Encode password  for a user you create or modify (you must use the component tLDAPAdOutput which can use byte[])

- Transform Dates

- Cacul and add userAccountControl 

<img src='./components/tLDAPPreparAuthAD/sample.jpg'>
