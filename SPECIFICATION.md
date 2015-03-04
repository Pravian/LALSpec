=== Linebased Account List (LAL) ===
Version: 1.0
Author: Overlord

Format:
  login:password (migrated-username) [old-password] {e-mail}

Notes:
  A dead (invalid) login should be prefixed with a dot (.) character.
  A login with an hidden password can have its password replaced with "<mypass>"

Examples:
  myuser@email.com:mypass (SuperCoolUsername)
  myusername:mypass {myuser@email.com)
  myusername:changedpassword [myoldpassword] {fakemail@email.com}
  .deadaccount:password {myemail@nope.com}
  some@user.com:<mypass> [ThisUser] 
