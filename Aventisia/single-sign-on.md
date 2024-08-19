# Single sign-on
Learn how to set up SSO for your Aventisia workspace.

Aventisia supports Single-Sign-On (SSO) for Enterprise plans.

SSO can be set up in Aventisia by a workspace admin following these steps:

+ From the Security panel in Workspace settings, verify each of the domains that you wish for SAML to apply to. For example, if you wish for aventisia.com to be covered by your SAML installation, you must verify aventisia.com using our DNS challenge method

+ Once verified, click Enable SAML which will present the SAML configuration options

+ Upload your IDP certificate and set the IDP Sign In URL

+ Lastly, retrieve your unique SAML SP url for IDP-initiated flows from inside of the settings panel

You'll need to ensure that the NameID is the email address of the user - this is how we match the account to the SAML token.