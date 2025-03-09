# VDC SETUP

```bash
git clone https://[TOKEN]@github.com/VasieDma/btcpayserver-docker

export BTCPAY_HOST="pay.vasie-dma.com"
export NBITCOIN_NETWORK="mainnet"
export BTCPAYGEN_CRYPTO1="btc"
export BTCPAYGEN_CRYPTO2="ltc"
export BTCPAYGEN_LIGHTNING="clightning"
export BTCPAYGEN_REVERSEPROXY="none"
export REVERSEPROXY_DEFAULT_HOST="$BTCPAY_HOST"

cd btcpayserver-docker
. ./btcpay-setup.sh -i
```
