# WebMoney-Miner
A lightweight Windows app for Monero mining with fast payouts to WebMoney (M-wallet) accounts.

## How to use
1. [Download](https://github.com/SIADigimoney/WebMoney-Miner/releases/tag/v1.0.0/WebMoneyMinerSetup.exe) and install
2. Launch the program and enter your WMID
3. Select the number of physical CPU cores and start mining

## Notes
- Your antivirus software may block our miner. Please add it to the exclusions list.
- Mining uses only physical CPU cores. Hyper-threading is not taken into account.
- If your CPU frequency drops when all cores are under load, try freeing up one or two cores to improve overall performance.
- Mining efficiency depends on your CPU power and the time the program runs.
- It is recommended to mine continuously to achieve stable and maximum income. The current 10-minute hashrate on the server may differ from the miner or show zero, as the server only accounts for hashrate based on accepted shares. In any case, the total hashrate over time will reflect your actual performance.
- Mining increases your computer's electricity consumption.
- Pay attention to the Huge Pages values in the miner log — after startup they should be 100%. If Huge Pages are not initialized correctly, restart your computer. Huge Pages can boost hashrate by up to 50%.

## End User License Agreement (EULA)
- Purpose of the Software
  - The software is intended exclusively for voluntary Monero mining with payments to M-wallet WebMoney, using your computer's computational resources.
- Terms of Use
  - The software operates only when explicitly launched by you.
  - You can stop mining or remove the software at any time.
  - Responsibility for using the software and possible consequences (heating, wear, electricity consumption) lies entirely with the user.
- Privacy
  - The software does not collect any data except your unique identifier in the WebMoney system (WMID) which is used to calculate rewards. The software does not transmit any data to third parties.
- Removal
  - To remove the software, use standard Windows tools ("Programs and Features"). After removal, no hidden components remain.
- Warranties and Liability
  - The software is provided "as is" (AS IS), without express or implied warranties.
  - All actions related to using the software are performed at your own risk.
