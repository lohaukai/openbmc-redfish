# openbmc
# Rest Server using Bottle to implement Redfish APIs

# Implements redifsh APIs using bottle for Board Management Controller using
# Dbus interface for querying, and performing tasks.
# This code must comply to pep8 and redfish standards
# Redfish uses HTTP operations including GET, PUT, PATCH, POST, DELETE, HEAD.
# GET retrieves data. POST is used for creating resources or to use actions.
# DELETE will delete a resource, but there are currently only a few resources
# that can be deleted.  PATCH is used to change one or more
# properties on a resource, while PUT is used to replace a resource entirely
# (though only a few resources can be completely replaced).  HEAD is similar to
# GET without the body data returned, and can be used for figuring out the URI
# structure by programs accessing a Redfish implementation.
