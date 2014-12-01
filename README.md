Django-payu
===========

What is PayU
============
PayU is India's most comprehensive payment gateway with credit cards, debit cards and netbanking. Go live with all payment options fastest in India

How to install Django-payu
==========================

	git clone https://github.com/krishnadaszorse/Django-payu.git
	cd Django-payu/PayU 
	python setup.py install

Setup in your project
=====================

in settings.py

add 'payu' in INSTALLED_APPS
add PAYU_INFO

	PAYU_INFO = {'merchant_key': "C0Dr8m",
	             'merchant_salt': "3sf0jURk",
	             # for production environment use 'https://secure.payu.in/_payment'
	             'payment_url': 'https://test.payu.in/_payment',
	}


Check out demo for learn how to integrate views