Creating a virtual environemtn for the jupyter notebook so that all the dependencies are not installed in the golbal environement.
The dependencies required will be mentioned in a requirements.txt file which can then be installed in one go.

1. Setting up a VIRTUAL ENVIRONMENT
    (a) Creating a virtual environement
        python -m venv venv
        (second venv is the name of the v. environment)

        -- for this I have the virtual env names "housing_prices_environment"
        
    (b) Activating the virtual environment
        source venv/Scripts/activate
        (You will see "venv" infront of the termianal's lines)