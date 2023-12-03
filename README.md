# Crypto_Clustering
Challenge Assignment for Unsupervised Learning

Layout for assignment ipynb file came from starter file.

Specific sections directly using sources listed below:

--------------------------------------------------
Setup 
--------------------------------------------------

The following was provided in starter files:

    # Import required libraries and dependencies
    import pandas as pd
    import hvplot.pandas
    from sklearn.cluster import KMeans
    from sklearn.decomposition import PCA
    from sklearn.preprocessing import StandardScaler

    # Load the data into a Pandas DataFrame
    df_market_data = pd.read_csv(
        "Resources/crypto_market_data.csv",
        index_col="coin_id")

    # Display sample data
    df_market_data.head(10)

    # Generate summary statistics
    df_market_data.describe()

    # Plot your data to see what's in your DataFrame
    df_market_data.hvplot.line(
    width=800,
    height=400,
    rot=90
    )

--------------------------------------------------
Find the Best Value for k Using the Original Data
--------------------------------------------------

The following section:

    k_df.hvplot.line(
    width=800,
    height=400,
    rot=90
    )

Used the same sytax/layout as the graph provided in the setup section above.

--------------------------------------------------
Cluster Cryptocurrencies with K-means 
Using the Original Data
--------------------------------------------------

As did the following formatting in this section:

    width=800,
    height=400

--------------------------------------------------
Find the Best Value for k Using the PCA Data
--------------------------------------------------

The code in this section used much of the same code as in
the "Find the Best Value for k Using the Original Data." section.


