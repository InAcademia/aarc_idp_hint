# aarc_idp_hint
This repository contains a list of institutions that support InAcademia and allows a servcie to hint to InAcademia where to try validation of the users affiliation

# About IdP_hinting 
IdP_hinting is an extension to the InAcademia service that intends to assist merchants who are keen to optimise the number of clicks a user needs to make in validating academic affiliation at the point of sale or registration. By making a list of uniquely referenced IdPs available on a country-by-country basis, it is possible for the merchant to target specific institutions or subsets of institutions with specific campaigns.

The IdP Hinting feature is based on a list of supported academic institutions as announced to eduGAIN. When IdP hinting is used as designed by the merchant, it will allow Academia to directly route a user to the selected institution's login page, without the need for the user to select its preferred institution from an academic discovery service.

Institutions will sometimes change the technical infrastructure InAcademia relies on to validate a user, e.g. with a new version of their software, or when the name of the institution changes. In such cases the IdP hints included in the merchant request must also be up to date. While these changes are not frequent on a per institution level, it is still recommended to consume and automatically refresh the list a merchant used on at least a nightly basis. 

In the event that a merchant request includes a stale or invalid IdP hint, the session will redirect to the merchant redirect_uri.

Please refer to https://inacademia.org/oidc-implementation-for-inacademia/ and https://inacademia.org/inacademia-implementation-guidelines/ for more information on implementation, features, design and desired behaviours.

# Permitted use
This content may only be utilised by organisations in posession of an executed service agreement to access InAcademia
