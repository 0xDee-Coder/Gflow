# Gflow

## Installation
1. Create Screen 
```bash
screen -S flow3_v2
```
1.1 Clone this repository
```bash
git clone https://github.com/0xDee-Coder/Gflow.git
cd Gflow
```
- set the ref_code in the .env file and 2capcha key
```bash
nano .env
```
2. Install dependencies
```bash
npm install
```
2.1. Edit accounts.txt should contain account information in the format: `email|pass`
```bash
nano accounts.txt
```
2.2. Edit register.txt should contain registration account info in the format: `email|pass`
- (You need to provide these manually, as emails may later need to be verified. It's recommended not to use Hotmail or temporary email services.)
```bash
nano register.txt
```
3. Fill Data and Proxy (Optional) `http://user:pass@ip:port`

```bash
nano proxy.txt
```
5. Add Private Key
```bash
nano privateKeys.txt
```
5. Run Bot
```bash
node main
```
6. Run Auto Ref Bot (Optional)
```
node autoref
```
## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This bot is for educational purposes only. Use it at your own risk. The developer is not responsible for any account-related issues or potential losses.
