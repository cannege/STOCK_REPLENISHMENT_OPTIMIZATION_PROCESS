# STOCK LEVEL REPLENISHMENT OPTIMIZATION
This group project endeavors to optimize the stock replenishment process of a fashion retail brand in Turkey. The primary objective of this effort is to minimize lost sales in stores that have a higher probability of sales and to prevent the detrimental impact of idle stock in underperforming stores in order to maximize the overall profit of the company. To achieve this goal, we must accurately determine the appropriate quantities of products to be dispatched from the warehouse to the various stores. To accomplish this, we first employ the moving average method to forecast the demand for each product-store pairing. Subsequently, we construct two mathematical models that incorporate these forecast values as parameters. Furthermore, all business rules and constraints provided by the company are taken into consideration while developing these mathematical models. The models are then solved using the commercial solver Gurobi. Additionally, sensitivity analysis is conducted on a small problem instance by making alterations to the parameters.