task1 1:
<!-- Any element with class title -->
.title{

}
<!-- Any element with id nav -->
#nav{

}
<!-- Any div in page -->
div{

}
<!-- Any h2 in page -->
h2{

}

------------------------------- task1 2: ---------------------------------
<!-- Extrnal -->
<link rel="stylesheet" href="css/file.css" />

<!-- Internal -->
<style>
p{
    color: red;
}
</style>

<!-- Inline style -->
<p style="color: blue;">This is our paragraph</p>
------------------------------------------------------------------------------
task 3 -> index.html
task 4 -> index.html

------------------------------- task1 5: --------------------------------
<!-- Valid -->
._user-name {
}

<!-- Valid -->
.-user-name {
}

<!-- Not Valid -->
.1user-name {
}

<!-- Not Valid -->
.@user-name {
}

<!-- Not Valid -->
.user@name {
}

<!-- Valid -->
._user10name {
}

<!-- Valid -->
.u {
}

-------------------------- task 6: --------------------------
<!-- Bad -->
.USERNAME {
}

<!-- Bad -->
.UserName {
}

<!-- Good -->
.user-name {
}

<!-- Bad -->
.userName {
}

<!-- Bad -->
.usernameprofile {
}