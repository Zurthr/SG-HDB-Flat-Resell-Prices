# Model for Resale Flat Prices in Singaporean HDB Units

A predictive machine learning model for the resale flat prices for Singaporean HDB units, based on their location and registration date

Uses RandomForestRegressor, and achieved an RSquared of 0.88 / 88% for the base model (1 extra column, being the age of the HDB) - Took around 5 minutes to fit, careful!

WIP a model with geographical feature as an additional point, see below

# Geographical Features
| Region  | Major Center (Planned or Existing) | Notes                                                                 |
|---------|-------------------------------------|-----------------------------------------------------------------------|
|**Central**|**Raffles Place** |Existing CBD, Raffles Place
| **West**  | **Jurong East** (Jurong Lake District) | Singapore’s *second CBD* in development; major hub for business, retail, and transport. |
| **East**  | **Tampines**                      | Established regional center; home to major malls, offices, and government services. |
| **North** | **Woodlands**                     | Developing into a business hub under the *Woodlands Regional Centre* plan. |
| **South** | **HarbourFront / Greater Southern Waterfront** | Future growth area; includes port redevelopment into live-work-play zone. |

# Dataset

Check out the dataset: [Resale flat prices based on registration date from Jan-2017 onwards](https://data.gov.sg/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view)

