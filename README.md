MAGIC backend API Documentation
==========================================
*API for MAGIC backend*

What's the license?
-------------------

magic-backend is distributed under the terms of The MIT License.

Who's responsible?
-------------------
Andrea Tramacere

ISDC Data Centre for Astrophysics, Astronomy Department of the University of Geneva, Chemin d'Ecogia 16, CH-1290 Versoix, Switzerland


Installation
------------
Clone the repository `git clone https://github.com/andreatramacere/magic-backend`

cd to the `magic-backend` directory 

* using Anaconda
 
     * `conda config --add channels conda-forge`
     * `conda install --file requirements.txt`
    
* or using PIP
     * `pip install -r requirements.txt`

* `python setup.py install`

Testing 
-------
- cd to the `test_examples` directory 

-  run the app: `run_magic_back_end.py`
 
1) with the notebook
    
    * browse this url to get api doc `http://localhost:5001/`
        * check the backend API doc
    
    * open the `magic-test.ipynb` notebook
    
2) with the frontend

  * browse this url `http://localhost:5001/index`
   