
"""
WSGI config for gettingstarted project.
It exposes the WSGI callable as a module-level variable named ``application``.
For more information on this file, see
https://docs.djangoproject.com/en/1.6/howto/deployment/wsgi/
"""


from simple_salesforce import Salesforce
sf = Salesforce(username='vdilipkumar7@trailhead.com', password='Vdk@1234', security_token='aQoMjNgsgYzmLe2a0HAbwiDnz')
sf.Contact.create({'LastName':'Smith','Email':'example@example.com'})
sf.Contact.update('003e0000003GuNXAA0',{'LastName': 'Jones', 'FirstName': 'John'})
sf.Contact.delete('003e0000003GuNXAA0')
sf.query("SELECT Id, Email FROM Contact WHERE LastName = 'Jones'")


