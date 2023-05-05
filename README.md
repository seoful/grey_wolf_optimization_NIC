# 🐺Grey Wolf Optimizer for feature selection
### Example of transaction fraud detection
Grey Wolf Optimizer (GWO) is a population-based optimization algorithm inspired by the social hierarchy and hunting behavior of grey wolves. This work observes its performance as a feature selectiong technique for transaction fraud detection.

## How to use it
You nead to load the data from this [link](https://www.kaggle.com/competitions/ieee-fraud-detection/data) to the core folder.

## Dataset
The [dataset](https://www.kaggle.com/competitions/ieee-fraud-detection/data) 
that was used was taken from the IEEE CIS Fraud Detection competition on Kaggle. It was provided by Vesta Corp.

* The dataset contains 2 tables: `transaction` and `identity` which are linked through the `TransactionId` field.
* The first table: 393 features and 590 040 records in the train set. 
* The second table: 41 columns and 144 233 records.
* The target column: `isFraud`

## Model
After analyzing various studies it was decided to use the Decision Tree classifier for this experiment.

## Libraries
This implementation is used such tools as:
* `pandas`
* `numpy`
* `tqdm`
* `sklearn`

## ✨Contributors✨
Thanks goes to these wonderful people:
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
   <td align="center" width = "185px"><a href="https://github.com/seoful"><img src="https://avatars.githubusercontent.com/u/34482712?v=4" width="100px;" alt=""/ class="avatar"><br /> <b>Aleksander Agafonov</b></a><br /> <sub><b><a href="mailto:a.agafonov@innopolis.university" title="mail to Aleksander">contact</a></b></sub><br /></td>
   <td align="center" width = "185px"><a href="https://github.com/swansofapollo"><img src="https://avatars.githubusercontent.com/u/74914481?v=4" width="100px;" alt=""/><br /> <b>Daria Lebedeva</b></a><br /> <sub><b><a href="mailto:d.lebedeva@innopolis.university" title="mail to Daria">contact</a></b></sub><br /></td>
   <td align="center" width = "185px"><a href="https://github.com/Poleeknow"><img src="https://avatars.githubusercontent.com/u/106336793?v=4" width="100px;" alt=""/><br /> <b>Polina Bazhenova</b></a><br /> <sub><b><a href="mailto:p.bazhenova@innopolis.university" title="mail to Polina">contact</a></b></sub><br /></td>
</tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
