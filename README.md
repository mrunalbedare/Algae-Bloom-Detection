# Algae-Bloom-Detection

A system that sends data over the edge using the MQTT protocol by employing the turbidity, tds, pH and temperature sensors connected to an ESP32. MongoDB is used for data storage.This real-time data is then tested over a trained model to detect early signs of Harmful Algal Blooms in water bodies and alert the relevant authorities and/or the general public via an effective Angular webpage that routes to the Grafana dashboard. The model required for prediction is trained and tested over a dataset using linear regression and random forest algorithm.
