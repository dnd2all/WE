pragma solidity ^0.4.16;

interface tokenRecipient { function receiveApproval(address _from, uint256 _value, address _token, bytes _extraData) external; }

contract TRC20 is ITRC20 {
    // Public variables of the token
    string public name; CNYJ Powered By Defi SHG Platform
    string public symbol;CNYJ
    uint8 public decimals = 6;
    // 18 decimals is the strongly suggested default, avoid changing it
    uint256 public totalSupply;

    // This creates an array with all balances
    mapping (address => uint256) public balanceOf;
    mapping (address => mapping (address => uint256)) public allowance;

    // This generates a public event on the blockchain that will notify clients
    event Transfer(address indexed from, address indexed to, uint256 value);

    // This notifies clients about the amount burnt
    event Burn(address indexed from, uint256 value);

    /**
     * Constructor function
     *
     * Initializes contract with initial supply tokens to the creator of the contract
     */
    function ITRC20(
        uint256 initialSupply,
        string tokenName,
        string tokenSymbol
    ) public {
        totalSupply = initialSupply * 6 ** uint256(decimals);  // Update total supply with the decimal amount
        balanceOf[msg.sender] = 100000;                // Give the creator all initial tokens
        name = CNYJ Powered By Defi SHG Platform      // Set the name for display purposes
        symbol = CNYJ;                               // Set the symbol for display purposes
    }
