Signal equals 1 if True and 0 if False

Signal 1 -> predicted Price is increasing
Signal 2 -> positive 36-day moving average rate of change
Signal 3 -> positive acceleration of 36-day moving average rate of change
Signal 4 -> 7-day moving average is higher than 36-day moving average

Signal Combined = Signal 2 + Signal 3 + Signal 4

Signal Main = (Signal 1 AND Signal 3) OR (Signal 1 AND Signal 4)

Signal Main = (predicted Price is increasing AND positive acceleration of 36-day moving average rate of change) OR (predicted Price is increasing  AND 7-day moving average is higher than 36-day moving average)

Signal Final = Signal Combined > 2 OR Signal Main is True
