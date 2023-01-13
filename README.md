# SWR-detection

SWR-detection is a collection of Spike2 scripts to help you detect the onset and termination of sharp-wave ripples and cortical slow waves. 
It is written for rodent recordings of the hippocampus and cortex. 
The program uses sleep states detected by [Sleep Stage Detection](https://ced.co.uk/files/scripts/RatSleepAuto.zip) to restrict the search for sharp-wave ripples and slow waves to NREM periods. If you also have detected spikes, the program will output peri-event histograms referenced to the onset of the sharp-wave ripple and waveform averages calculated from LFP channels. 


Screenshot

![image](https://user-images.githubusercontent.com/49167439/212425374-bf55413e-343f-474b-ad57-ed21cdb3cfcd.png)
![image](https://user-images.githubusercontent.com/49167439/212425418-1f9b3f0c-0b01-4a6b-8ec0-d22de0b74597.png)


### Dependencies

- Spike2 version 10
- [Sleep Stage Detection](https://ced.co.uk/files/scripts/RatSleepAuto.zip)

## How to use

- Use [Sleep Stage Detection](https://ced.co.uk/files/scripts/RatSleepAuto.zip) to first detect NREM states from local field potential and electromyographic recordings. 
- Run SWR-detection using Script → Run Script →  Load and Run...
- Navigate to path where you saved SWR-detection.


## Built With

- [Spike2](https://ced.co.uk/img/Spike10.pdf)

## Future Updates

- [ ] 

## Author

**Diellor Basha**

- [Profile](https://github.com/DiellorBasha "DiellorBasha")
- [Email](mailto:diellorbasha@gmail.com?subject=Hi "Hi!")
- [Website](https://www.linkedin.com/in/diellor-basha-512b82171/)

## 🤝 Support

Contributions, issues, and feature requests are welcome!

Give a ⭐️ if you like this project!
