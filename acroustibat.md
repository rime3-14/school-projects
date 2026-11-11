# AcroustiBat

**INSA Lyon · 2A · Team project**

AcroustiBat measures acoustic patterns inside a building. The ESP32 gathers microphone samples, computes a frequency spectrum and sends the spectrum and sensor readings over MQTT. Python tools store the readings and visualize the spatial distribution of amplitudes.

I worked on outlier filtering, clustering and visualization. An offline demo checks a 440 Hz FFT peak and the original filter using synthetic measurements. Live data capture uses the original ESP32 and sensor setup. The cleaned source snapshot is private.
