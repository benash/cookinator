# Cookinator lets you manipulate cookies.

    Cookinator.load(:chrome)
    Cookinator.load(:safari)
    Cookinator.load(:firefox)
    Cookinator.load(:ie)
    Cookinator.load(:konqueror)
    Cookinator.load(:cookiestxt)

    Cookinator.load(format, options = {})
    Cookinator.save(format, options = {})

    options = { :dbpath => '/Users/asdf/cookies.sqlite' }

