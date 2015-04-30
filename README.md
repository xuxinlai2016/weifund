# WeiFund

A decentralized, fully transparent, open source crowdfunding DApp built on Ethereum.

<img src="app/public/images/screen0.jpg" />

## <a name="installation"></a> Installation

1. Clone this repo and run the DApp.
   
    ```
    $ git clone -b meteor https://github.com/WeiFund/WeiFund.git
    $ cd WeiFund/app
    $ meteor
    ```
    
2. Start an eth node open `http://localhost:3000` in *mist*, *mix* or *alethzero* or run geth locally, as follows:

    ```
    $ geth --rpc --rpcaddr="localhost" --loglevel=5 --maxpeers=0 --rpccorsdomain="http://localhost:3000" --unlock=primary --mine
    ```

3. Go to `http://localhost:3000/admin`

    Click "Deploy" and copy the address provided

4. Edit `app/client/lib/weifundConfig.js`

    Change `WeiFund.address` to the new address provided

5. Refresh and run WeiFund!
