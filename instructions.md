# Human Software
Author: vjh240
## Brushing Teeth
1. Approach Sink
2. Pick up ToothBrush.Handle
3. Apply Toothpaste to ToothBrush.Head
4. Turn on ColdWater
5. Hold ToothBrush.Head under Faucet (1 second)
6. Turn off ColdWater
7. Open Mouth
8. Brush All Teeth with ToothBrush.Head (120 seconds)
9. Spit into Sink
10. Turn on ColdWater
11. Drink ColdWater (2 seconds)
12. Turn off ColdWater
13. Rinse (5 seconds)
14. Spit into Sink
15. Place ToothBrush
16. Use Towel to Dry Mouth
17. Look at Mirror
18. Inspect Teeth
19. If Teeth.Dirty = True then GoTo 2

## Commute to Work
Exit Home
If Weather.Precipitation = False and Weather.Temperature > 70 Then
	Walk to GreenLine.station.UnionSquare
	Enter Subway
Else
	Walk to GreyLine.station.FirstAve
	Enter Subway
	Enter GreyLine.direction.EighthAve
	Exit GreyLine.station.UnionSquare
EndIf
If GreenLine.Number < 6 Then
	Enter GreenLine.direction.BowlingGreen
	Exit GreenLine.station.FultonStreet
	Exit Subway
EndIf
Walk to FederalReserve.location.MaidenLane
Enter FederalReserve
