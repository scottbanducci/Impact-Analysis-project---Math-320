# Impact-Analysis-project---Math-320

This project was for UBC's MATH320 course on Linear Programming.

Using Jupyter notebooks and the Simplex algorithm, we delivered a mock analysis of the housing market in Vancouver for Mayor. The objective was to "find the optimal number of new 5+ story apartment buildings to build in the City of Vancouver given our resource limitations and the continuance of Kennedy Stewart’s Mayorship".

We chose to split the city into 3 geographical zones, consider 3 sizes residential building and established 5 constraint variables (Political capital, Traffic congestion, Public Sentiment / Media Coverage, Private Interests (Developers), Pollution / Environmental Impact). We then estimated which coefficients to assign to each zone+building pair to create our constraints. Using the Revised Simplex Method from the PuLP python library, we determined the optimal distribution of City resources to maximize new residences while ensuring the Mayor has enough political capital to win the next election.

