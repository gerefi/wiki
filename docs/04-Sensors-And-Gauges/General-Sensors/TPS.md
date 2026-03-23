# Throttle position 

Throttle position sensors are used to tell the gerefi ECU the angle of the throttle blade. Most are 3 wire: 

1: Power (Provided from gerefi ECU Power Output)
2: Ground (provided from gerefi ECU Ground Output)
3: Signal (sent to gerefi ECU Lowside input)

*ensuring power and ground come from the gerefi ECU will make sure the signal is clean and consistent)

For vehicles with electric throttle bodies, throttle position sensors will need to always have two redundant signals (usually opposite ie 0-5v and 5-0v). This is to ensure safety of the operation of the vehicle.
