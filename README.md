The world is already facing a shortage of fresh water, and extreme climate changes have
worsened the situation. This has intensified the need for sustainable water management,
especially for water-intensive crops like rice, which alone accounts for nearly 40% of the total
water used for irrigation. Traditionally, farmers heavily depend on static calendars or their
past experience for watering crops. However, these methods fail to adapt to continuously
changing weather, which results in both water wastage and compromised crop productivity.
To solve this, this chapter introduces an experimental and AI-driven irrigation framework.
This framework uses historical weather and environmental data, covering many years of
planting and harvesting, to forecast rice irrigation water requirements.
To find the best way to predict soil moisture, we tested our proposed framework with
seven different models, moving from simple math to advanced AI. We started with basic
statistical tools like AR, MA, and ARMA to establish a baseline in order to see how well
simple math can predict the soil moisture. Then, we tested ARIMA and SARIMA to
see if they could handle seasonal farming trends better. Finally, we applied deep learning
networks Gated Recurrent Unit (GRU) and Long Short-Term Memory (LSTM) since they
are designed to understand highly complex, long-term weather patterns.
We evaluated the models using 24 years (2000–2023) of real-world weather and soil data,
which consist of temperature, rainfall, relative humidity, solar radiation, and soil moisture.
To see which model performed best, we evaluated them using RMSE, MAE, R2 , and MAPE
scores. We found that as the models became more advanced and complex, their accuracy
improved. The GRU model was the clear winner, achieving an R2 of 0.9789 and beating
the LSTM. Ultimately, this proves that deep learning can serve as a highly reliable tool
for farmers. By using AI to schedule irrigation, we can save water and support global
sustainability goals.
