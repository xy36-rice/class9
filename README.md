# class9

1. Write the null and alternative hypotheses you would use to test each of the following situations:
- Is a coin fair?
	* Null: The chance that the coin lands on heads in the coin toss is 50%.
	* Alter: The chance that the coin lands on heads in the coin toss is not 50%.
- Only about 20% of people who try to quit smoking succeed. Sellers of a motivational tape claim that listening to the recorded messages can help people quit.
	* Null: At most 20% of people who listen to the recorded messages quit smoking.
	* Alter: More than 20% of people who listen to the recorded messages quit smoking.
- In the 1950s only about 40% of high school graduates went on to college. Has this percentage changed?
	* Null: The percentage that high school graduates go on to college is 40% after the 1950s.
	* Alter: The percentage that high school graduates go on to college is not 40% after the 1950s.
- We field test a new type of pipette, planning to market it only if we are sure that at least 60% of people like the new version.
	* Null: Less than 60% of people like the new version of the pipette.
	* Alter: At least 60% of people like the new version of the pipette.


2. A survey investigating whether the proportion of today’s high school seniors who own their own cars is higher than it was a decade ago finds a p-value of 0.017. Is it reasonable to conclude that more high schoolers have cars? Explain.
	* It depends on the significance level. H0 will be rejected if the p-value is lower than the significance level. For example:
		* If we set the significance level to 0.01, the answer is no.
		* If we set the significance level to 0.05, the answer is yes.
	* H0 is a no difference hypothesis. Therefore,
	* H0: Today’s high school seniors who own their own cars are not higher than it was a decade ago. 
	* Ha: Today’s high school seniors who own their own cars are higher than it was a decade ago. 


3. A medical researcher tested a new treatment for poison ivy against the traditional ointment. With a p-value of 0.047 she concludes the new treatment is more effective. What does the p-value mean in this context?
	* H0: New treatment for poison ivy is not more effective than the traditional ointment.
	* Ha: New treatment for poison ivy is more effective than the traditional ointment.
	* The probability that rejects H0 given H0 is true is 0.047.


4. Have harsher penalties and ad campaigns increased seatbelt use? Observations of commuter traffic failed to find evidence of a significant change compared with three years ago. What does the study’s p-value of 0.17 means in this context?
	* H0: By having harsher penalties and ad campaigns, seatbelt usage does not increase.
	* Ha: By having harsher penalties and ad campaigns, seatbelt usage increases.
	* p is higher than alpha (significance level), so it fails to reject H0.


5. Researcher developing scanners to search for hidden weapons at airports concluded that a new device is significantly better than the current scanner. They made this decision based on a test using alpha = 0.05. Would they have made the same decision at alpha = 0.10 or alpha = 0.01? Explain
	* H0: A new device is not significantly better than the current scanner
	* Ha: A new device is significantly better than the current scanner
	* When alpha = 0.05, H0 has been rejected, so p-value < 0.05 < 0.10.
		* When alpha = 0.10, H0 must be also rejected, so the same decision will be made
		* When alpha = 0.01, it is hard to compare, so the decision may change or not change.


6. Environmentalists concerned about the impact of high-frequency radio transmissions on birds found that there was no evidence of a higher mortality rate among hatchlings in nests near cell towers. They based this conclusion on a test using alpha = 0.05. Would they have made the same decision at alpha = 0.10? How about alpha = 0.01? Explain.
	* H0: High-frequency radio transmissions on birds do not lead to a higher mortality rate among hatchlings in nests near cell towers.
	* Ha: High-frequency radio transmissions on birds lead to a higher mortality rate among hatchlings in nests near cell towers.
	* When alpha = 0.05, it is failed to reject H0, so 0.01 < 0.05 < p-value.
		* When alpha = 0.01, it will be also failed to reject H0, so the same conclusion will be drawn.
		* When alpha = 0.10, it is hard to compare, so the conclusion may change or not change.


7. A clean air standard requires that vehicle exhaust emissions not exceed specified limits for various pollutants. Many states require that cars be tested annually to make sure they meet the standards. Suppose state regulators double check a random sample of cars that a suspect repair shop has certified as okay. They will revoke the shop’s license if they find significant evidence that the shop is certifying vehicles that do not meet standards. 	
	* H0: The shop does not certify vehicles that do not meet standards.
	* Ha: The shop is certifying vehicles that do not meet standards.
- In this context, what is a Type I error?
	* The shop does not certify vehicles that do not meet standards, but state regulators think they do. (H0 is rejected given H0 is true)
- In this context, what is a Type II error?
	* The shop is certifying vehicles that do not meet standards, but regulators do not think so. (Failed to reject H0 given H0 is false)
- Which type of error would the shop’s owner consider more serious?
	* Type I error.
- Which type of error might environmentalists consider more serious?
	* Type II error.
