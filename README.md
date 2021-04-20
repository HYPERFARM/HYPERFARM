constructor () {
        _name = "HYPERFARM";
        _symbol = "HF";
        _totalSupply = 2600000000*10**(decimals());
        _balances[_msgSender()] = _totalSupply;
