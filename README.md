Carbono
=======

0. OBJECTIVE

	0. Manage market.

0. INSTALLING

	0. Install the redis database dependency.

		>  # apt-get install redis-server

	
	0. If you don't have pip (python package manager), we recommend to install it.

		>  # apt-get install python-pip

    0. Install python webkit 

        >  # apt-get install python-webkit

	0. Then install tornado web framework and redis client for python.
		
		>  # pip install tornado redis

	0. Generate certificate to handle https requests.

		> $ ./gen_certificate.sh

    0. Create admin account.

        > $ python create_admin.py

0. RUNNING

	0. Run the server.

		> $ python server.py

	0. Then load application from your web browser with address:

		> http://localhost:8000/

    0. Then load application from webapp:

        > ./run-carbono.sh
