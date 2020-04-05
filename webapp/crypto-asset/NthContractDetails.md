# Token Name / Symbol

NthopinionToken / NTH

# NTH Contract Address

0x60293bd11de6cce1c7fd87a96747d6099a020cd0

# Public Key Address PATIENT1

0x7462BcC97086A79a6310B425F408014705cD1fcA

  Associated Rinkeby Test Wallet Private Key (demo): fc09cf137598d81d45c91c07fb310f0714139c0992d119d88af776e21e63d0bf
  
# Public Key Address DOCTOR1

0x8Bc8f2CA3d78fe01A7E4bfb118761c751438b854

  Associated Private Key (demo): 3b95fb2b87bcbbc87150a0cbb889a1d45c25f3985825d6847c638c2943e70174

# Public Key Address ContractCreator

0x2aec6a487E96be3067046D7CfD69c3BcfB280c16

Metamask Private Key (demo): 79af02221bfeec47191c3831ff03586ce077f52ef729d7b8a4bba6777ea08ac3


# ABI

[ { "anonymous": false, "inputs": [ { "indexed": true, "name": "_owner", "type": "address" }, { "indexed": true, "name": "_spender", "type": "address" }, { "indexed": false, "name": "_value", "type": "uint256" } ], "name": "Approval", "type": "event" }, { "anonymous": false, "inputs": [ { "indexed": true, "name": "_from", "type": "address" }, { "indexed": true, "name": "_to", "type": "address" }, { "indexed": false, "name": "_value", "type": "uint256" } ], "name": "Transfer", "type": "event" }, { "constant": false, "inputs": [ { "name": "_spender", "type": "address" }, { "name": "_value", "type": "uint256" } ], "name": "approve", "outputs": [ { "name": "success", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_to", "type": "address" }, { "name": "_value", "type": "uint256" } ], "name": "transfer", "outputs": [ { "name": "success", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "constant": false, "inputs": [ { "name": "_from", "type": "address" }, { "name": "_to", "type": "address" }, { "name": "_value", "type": "uint256" } ], "name": "transferFrom", "outputs": [ { "name": "success", "type": "bool" } ], "payable": false, "stateMutability": "nonpayable", "type": "function" }, { "inputs": [ { "name": "_initialAmount", "type": "uint256" }, { "name": "_tokenName", "type": "string" }, { "name": "_decimalUnits", "type": "uint8" }, { "name": "_tokenSymbol", "type": "string" } ], "payable": false, "stateMutability": "nonpayable", "type": "constructor" }, { "constant": true, "inputs": [ { "name": "_owner", "type": "address" }, { "name": "_spender", "type": "address" } ], "name": "allowance", "outputs": [ { "name": "remaining", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "", "type": "address" }, { "name": "", "type": "address" } ], "name": "allowed", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "_owner", "type": "address" } ], "name": "balanceOf", "outputs": [ { "name": "balance", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [ { "name": "", "type": "address" } ], "name": "balances", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "decimals", "outputs": [ { "name": "", "type": "uint8" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "name", "outputs": [ { "name": "", "type": "string" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "symbol", "outputs": [ { "name": "", "type": "string" } ], "payable": false, "stateMutability": "view", "type": "function" }, { "constant": true, "inputs": [], "name": "totalSupply", "outputs": [ { "name": "", "type": "uint256" } ], "payable": false, "stateMutability": "view", "type": "function" } ]

# ByteCode

{ "linkReferences": {}, "object": "608060405234801561001057600080fd5b5060405161078638038061078683398101604090815281516020808401518385015160608601513360009081526001855295862085905594849055908501805193959094919391019161006891600391860190610095565b506004805460ff191660ff8416179055805161008b906005906020840190610095565b5050505050610130565b828054600181600116156101000203166002900490600052602060002090601f016020900481019282601f106100d657805160ff1916838001178555610103565b82800160010185558215610103579182015b828111156101035782518255916020019190600101906100e8565b5061010f929150610113565b5090565b61012d91905b8082111561010f5760008155600101610119565b90565b6106478061013f6000396000f3006080604052600436106100ae5763ffffffff7c010000000000000000000000000000000000000000000000000000000060003504166306fdde0381146100b3578063095ea7b31461013d57806318160ddd1461017557806323b872dd1461019c57806327e235e3146101c6578063313ce567146101e75780635c6581651461021257806370a082311461023957806395d89b411461025a578063a9059cbb1461026f578063dd62ed3e14610293575b600080fd5b3480156100bf57600080fd5b506100c86102ba565b6040805160208082528351818301528351919283929083019185019080838360005b838110156101025781810151838201526020016100ea565b50505050905090810190601f16801561012f5780820380516001836020036101000a031916815260200191505b509250505060405180910390f35b34801561014957600080fd5b50610161600160a060020a0360043516602435610348565b604080519115158252519081900360200190f35b34801561018157600080fd5b5061018a6103ae565b60408051918252519081900360200190f35b3480156101a857600080fd5b50610161600160a060020a03600435811690602435166044356103b4565b3480156101d257600080fd5b5061018a600160a060020a03600435166104b8565b3480156101f357600080fd5b506101fc6104ca565b6040805160ff9092168252519081900360200190f35b34801561021e57600080fd5b5061018a600160a060020a03600435811690602435166104d3565b34801561024557600080fd5b5061018a600160a060020a03600435166104f0565b34801561026657600080fd5b506100c861050b565b34801561027b57600080fd5b50610161600160a060020a0360043516602435610566565b34801561029f57600080fd5b5061018a600160a060020a03600435811690602435166105f0565b6003805460408051602060026001851615610100026000190190941693909304601f810184900484028201840190925281815292918301828280156103405780601f1061031557610100808354040283529160200191610340565b820191906000526020600020905b81548152906001019060200180831161032357829003601f168201915b505050505081565b336000818152600260209081526040808320600160a060020a038716808552908352818420869055815186815291519394909390927f8c5be1e5ebec7d5bd14f71427d1e84f3dd0314c0f7b2291e5b200ac8c7c3b925928290030190a350600192915050565b60005481565b600160a060020a0383166000818152600260209081526040808320338452825280832054938352600190915281205490919083118015906103f55750828110155b151561040057600080fd5b600160a060020a038085166000908152600160205260408082208054870190559187168152208054849003905560001981101561046257600160a060020a03851660009081526002602090815260408083203384529091529020805484900390555b83600160a060020a031685600160a060020a03167fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef856040518082815260200191505060405180910390a3506001949350505050565b60016020526000908152604090205481565b60045460ff1681565b600260209081526000928352604080842090915290825290205481565b600160a060020a031660009081526001602052604090205490565b6005805460408051602060026001851615610100026000190190941693909304601f810184900484028201840190925281815292918301828280156103405780601f1061031557610100808354040283529160200191610340565b3360009081526001602052604081205482111561058257600080fd5b33600081815260016020908152604080832080548790039055600160a060020a03871680845292819020805487019055805186815290519293927fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef929181900390910190a350600192915050565b600160a060020a039182166000908152600260209081526040808320939094168252919091522054905600a165627a7a7230582030a7b1cab72bc839f2c905ba3d66561d6c4f9a1642fd5e33f25099df6955828e0029", "opcodes": "PUSH1 0x80 PUSH1 0x40 MSTORE CALLVALUE DUP1 ISZERO PUSH2 0x10 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH1 0x40 MLOAD PUSH2 0x786 CODESIZE SUB DUP1 PUSH2 0x786 DUP4 CODECOPY DUP2 ADD PUSH1 0x40 SWAP1 DUP2 MSTORE DUP2 MLOAD PUSH1 0x20 DUP1 DUP5 ADD MLOAD DUP4 DUP6 ADD MLOAD PUSH1 0x60 DUP7 ADD MLOAD CALLER PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x1 DUP6 MSTORE SWAP6 DUP7 KECCAK256 DUP6 SWAP1 SSTORE SWAP5 DUP5 SWAP1 SSTORE SWAP1 DUP6 ADD DUP1 MLOAD SWAP4 SWAP6 SWAP1 SWAP5 SWAP2 SWAP4 SWAP2 ADD SWAP2 PUSH2 0x68 SWAP2 PUSH1 0x3 SWAP2 DUP7 ADD SWAP1 PUSH2 0x95 JUMP JUMPDEST POP PUSH1 0x4 DUP1 SLOAD PUSH1 0xFF NOT AND PUSH1 0xFF DUP5 AND OR SWAP1 SSTORE DUP1 MLOAD PUSH2 0x8B SWAP1 PUSH1 0x5 SWAP1 PUSH1 0x20 DUP5 ADD SWAP1 PUSH2 0x95 JUMP JUMPDEST POP POP POP POP POP PUSH2 0x130 JUMP JUMPDEST DUP3 DUP1 SLOAD PUSH1 0x1 DUP2 PUSH1 0x1 AND ISZERO PUSH2 0x100 MUL SUB AND PUSH1 0x2 SWAP1 DIV SWAP1 PUSH1 0x0 MSTORE PUSH1 0x20 PUSH1 0x0 KECCAK256 SWAP1 PUSH1 0x1F ADD PUSH1 0x20 SWAP1 DIV DUP2 ADD SWAP3 DUP3 PUSH1 0x1F LT PUSH2 0xD6 JUMPI DUP1 MLOAD PUSH1 0xFF NOT AND DUP4 DUP1 ADD OR DUP6 SSTORE PUSH2 0x103 JUMP JUMPDEST DUP3 DUP1 ADD PUSH1 0x1 ADD DUP6 SSTORE DUP3 ISZERO PUSH2 0x103 JUMPI SWAP2 DUP3 ADD JUMPDEST DUP3 DUP2 GT ISZERO PUSH2 0x103 JUMPI DUP3 MLOAD DUP3 SSTORE SWAP2 PUSH1 0x20 ADD SWAP2 SWAP1 PUSH1 0x1 ADD SWAP1 PUSH2 0xE8 JUMP JUMPDEST POP PUSH2 0x10F SWAP3 SWAP2 POP PUSH2 0x113 JUMP JUMPDEST POP SWAP1 JUMP JUMPDEST PUSH2 0x12D SWAP2 SWAP1 JUMPDEST DUP1 DUP3 GT ISZERO PUSH2 0x10F JUMPI PUSH1 0x0 DUP2 SSTORE PUSH1 0x1 ADD PUSH2 0x119 JUMP JUMPDEST SWAP1 JUMP JUMPDEST PUSH2 0x647 DUP1 PUSH2 0x13F PUSH1 0x0 CODECOPY PUSH1 0x0 RETURN STOP PUSH1 0x80 PUSH1 0x40 MSTORE PUSH1 0x4 CALLDATASIZE LT PUSH2 0xAE JUMPI PUSH4 0xFFFFFFFF PUSH29 0x100000000000000000000000000000000000000000000000000000000 PUSH1 0x0 CALLDATALOAD DIV AND PUSH4 0x6FDDE03 DUP2 EQ PUSH2 0xB3 JUMPI DUP1 PUSH4 0x95EA7B3 EQ PUSH2 0x13D JUMPI DUP1 PUSH4 0x18160DDD EQ PUSH2 0x175 JUMPI DUP1 PUSH4 0x23B872DD EQ PUSH2 0x19C JUMPI DUP1 PUSH4 0x27E235E3 EQ PUSH2 0x1C6 JUMPI DUP1 PUSH4 0x313CE567 EQ PUSH2 0x1E7 JUMPI DUP1 PUSH4 0x5C658165 EQ PUSH2 0x212 JUMPI DUP1 PUSH4 0x70A08231 EQ PUSH2 0x239 JUMPI DUP1 PUSH4 0x95D89B41 EQ PUSH2 0x25A JUMPI DUP1 PUSH4 0xA9059CBB EQ PUSH2 0x26F JUMPI DUP1 PUSH4 0xDD62ED3E EQ PUSH2 0x293 JUMPI JUMPDEST PUSH1 0x0 DUP1 REVERT JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0xBF JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0xC8 PUSH2 0x2BA JUMP JUMPDEST PUSH1 0x40 DUP1 MLOAD PUSH1 0x20 DUP1 DUP3 MSTORE DUP4 MLOAD DUP2 DUP4 ADD MSTORE DUP4 MLOAD SWAP2 SWAP3 DUP4 SWAP3 SWAP1 DUP4 ADD SWAP2 DUP6 ADD SWAP1 DUP1 DUP4 DUP4 PUSH1 0x0 JUMPDEST DUP4 DUP2 LT ISZERO PUSH2 0x102 JUMPI DUP2 DUP2 ADD MLOAD DUP4 DUP3 ADD MSTORE PUSH1 0x20 ADD PUSH2 0xEA JUMP JUMPDEST POP POP POP POP SWAP1 POP SWAP1 DUP2 ADD SWAP1 PUSH1 0x1F AND DUP1 ISZERO PUSH2 0x12F JUMPI DUP1 DUP3 SUB DUP1 MLOAD PUSH1 0x1 DUP4 PUSH1 0x20 SUB PUSH2 0x100 EXP SUB NOT AND DUP2 MSTORE PUSH1 0x20 ADD SWAP2 POP JUMPDEST POP SWAP3 POP POP POP PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x149 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x161 PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD AND PUSH1 0x24 CALLDATALOAD PUSH2 0x348 JUMP JUMPDEST PUSH1 0x40 DUP1 MLOAD SWAP2 ISZERO ISZERO DUP3 MSTORE MLOAD SWAP1 DUP2 SWAP1 SUB PUSH1 0x20 ADD SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x181 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x18A PUSH2 0x3AE JUMP JUMPDEST PUSH1 0x40 DUP1 MLOAD SWAP2 DUP3 MSTORE MLOAD SWAP1 DUP2 SWAP1 SUB PUSH1 0x20 ADD SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x1A8 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x161 PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD DUP2 AND SWAP1 PUSH1 0x24 CALLDATALOAD AND PUSH1 0x44 CALLDATALOAD PUSH2 0x3B4 JUMP JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x1D2 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x18A PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD AND PUSH2 0x4B8 JUMP JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x1F3 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x1FC PUSH2 0x4CA JUMP JUMPDEST PUSH1 0x40 DUP1 MLOAD PUSH1 0xFF SWAP1 SWAP3 AND DUP3 MSTORE MLOAD SWAP1 DUP2 SWAP1 SUB PUSH1 0x20 ADD SWAP1 RETURN JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x21E JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x18A PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD DUP2 AND SWAP1 PUSH1 0x24 CALLDATALOAD AND PUSH2 0x4D3 JUMP JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x245 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x18A PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD AND PUSH2 0x4F0 JUMP JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x266 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0xC8 PUSH2 0x50B JUMP JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x27B JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x161 PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD AND PUSH1 0x24 CALLDATALOAD PUSH2 0x566 JUMP JUMPDEST CALLVALUE DUP1 ISZERO PUSH2 0x29F JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST POP PUSH2 0x18A PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB PUSH1 0x4 CALLDATALOAD DUP2 AND SWAP1 PUSH1 0x24 CALLDATALOAD AND PUSH2 0x5F0 JUMP JUMPDEST PUSH1 0x3 DUP1 SLOAD PUSH1 0x40 DUP1 MLOAD PUSH1 0x20 PUSH1 0x2 PUSH1 0x1 DUP6 AND ISZERO PUSH2 0x100 MUL PUSH1 0x0 NOT ADD SWAP1 SWAP5 AND SWAP4 SWAP1 SWAP4 DIV PUSH1 0x1F DUP2 ADD DUP5 SWAP1 DIV DUP5 MUL DUP3 ADD DUP5 ADD SWAP1 SWAP3 MSTORE DUP2 DUP2 MSTORE SWAP3 SWAP2 DUP4 ADD DUP3 DUP3 DUP1 ISZERO PUSH2 0x340 JUMPI DUP1 PUSH1 0x1F LT PUSH2 0x315 JUMPI PUSH2 0x100 DUP1 DUP4 SLOAD DIV MUL DUP4 MSTORE SWAP2 PUSH1 0x20 ADD SWAP2 PUSH2 0x340 JUMP JUMPDEST DUP3 ADD SWAP2 SWAP1 PUSH1 0x0 MSTORE PUSH1 0x20 PUSH1 0x0 KECCAK256 SWAP1 JUMPDEST DUP2 SLOAD DUP2 MSTORE SWAP1 PUSH1 0x1 ADD SWAP1 PUSH1 0x20 ADD DUP1 DUP4 GT PUSH2 0x323 JUMPI DUP3 SWAP1 SUB PUSH1 0x1F AND DUP3 ADD SWAP2 JUMPDEST POP POP POP POP POP DUP2 JUMP JUMPDEST CALLER PUSH1 0x0 DUP2 DUP2 MSTORE PUSH1 0x2 PUSH1 0x20 SWAP1 DUP2 MSTORE PUSH1 0x40 DUP1 DUP4 KECCAK256 PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB DUP8 AND DUP1 DUP6 MSTORE SWAP1 DUP4 MSTORE DUP2 DUP5 KECCAK256 DUP7 SWAP1 SSTORE DUP2 MLOAD DUP7 DUP2 MSTORE SWAP2 MLOAD SWAP4 SWAP5 SWAP1 SWAP4 SWAP1 SWAP3 PUSH32 0x8C5BE1E5EBEC7D5BD14F71427D1E84F3DD0314C0F7B2291E5B200AC8C7C3B925 SWAP3 DUP3 SWAP1 SUB ADD SWAP1 LOG3 POP PUSH1 0x1 SWAP3 SWAP2 POP POP JUMP JUMPDEST PUSH1 0x0 SLOAD DUP2 JUMP JUMPDEST PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB DUP4 AND PUSH1 0x0 DUP2 DUP2 MSTORE PUSH1 0x2 PUSH1 0x20 SWAP1 DUP2 MSTORE PUSH1 0x40 DUP1 DUP4 KECCAK256 CALLER DUP5 MSTORE DUP3 MSTORE DUP1 DUP4 KECCAK256 SLOAD SWAP4 DUP4 MSTORE PUSH1 0x1 SWAP1 SWAP2 MSTORE DUP2 KECCAK256 SLOAD SWAP1 SWAP2 SWAP1 DUP4 GT DUP1 ISZERO SWAP1 PUSH2 0x3F5 JUMPI POP DUP3 DUP2 LT ISZERO JUMPDEST ISZERO ISZERO PUSH2 0x400 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB DUP1 DUP6 AND PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x1 PUSH1 0x20 MSTORE PUSH1 0x40 DUP1 DUP3 KECCAK256 DUP1 SLOAD DUP8 ADD SWAP1 SSTORE SWAP2 DUP8 AND DUP2 MSTORE KECCAK256 DUP1 SLOAD DUP5 SWAP1 SUB SWAP1 SSTORE PUSH1 0x0 NOT DUP2 LT ISZERO PUSH2 0x462 JUMPI PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB DUP6 AND PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x2 PUSH1 0x20 SWAP1 DUP2 MSTORE PUSH1 0x40 DUP1 DUP4 KECCAK256 CALLER DUP5 MSTORE SWAP1 SWAP2 MSTORE SWAP1 KECCAK256 DUP1 SLOAD DUP5 SWAP1 SUB SWAP1 SSTORE JUMPDEST DUP4 PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB AND DUP6 PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB AND PUSH32 0xDDF252AD1BE2C89B69C2B068FC378DAA952BA7F163C4A11628F55A4DF523B3EF DUP6 PUSH1 0x40 MLOAD DUP1 DUP3 DUP2 MSTORE PUSH1 0x20 ADD SWAP2 POP POP PUSH1 0x40 MLOAD DUP1 SWAP2 SUB SWAP1 LOG3 POP PUSH1 0x1 SWAP5 SWAP4 POP POP POP POP JUMP JUMPDEST PUSH1 0x1 PUSH1 0x20 MSTORE PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x40 SWAP1 KECCAK256 SLOAD DUP2 JUMP JUMPDEST PUSH1 0x4 SLOAD PUSH1 0xFF AND DUP2 JUMP JUMPDEST PUSH1 0x2 PUSH1 0x20 SWAP1 DUP2 MSTORE PUSH1 0x0 SWAP3 DUP4 MSTORE PUSH1 0x40 DUP1 DUP5 KECCAK256 SWAP1 SWAP2 MSTORE SWAP1 DUP3 MSTORE SWAP1 KECCAK256 SLOAD DUP2 JUMP JUMPDEST PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB AND PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x1 PUSH1 0x20 MSTORE PUSH1 0x40 SWAP1 KECCAK256 SLOAD SWAP1 JUMP JUMPDEST PUSH1 0x5 DUP1 SLOAD PUSH1 0x40 DUP1 MLOAD PUSH1 0x20 PUSH1 0x2 PUSH1 0x1 DUP6 AND ISZERO PUSH2 0x100 MUL PUSH1 0x0 NOT ADD SWAP1 SWAP5 AND SWAP4 SWAP1 SWAP4 DIV PUSH1 0x1F DUP2 ADD DUP5 SWAP1 DIV DUP5 MUL DUP3 ADD DUP5 ADD SWAP1 SWAP3 MSTORE DUP2 DUP2 MSTORE SWAP3 SWAP2 DUP4 ADD DUP3 DUP3 DUP1 ISZERO PUSH2 0x340 JUMPI DUP1 PUSH1 0x1F LT PUSH2 0x315 JUMPI PUSH2 0x100 DUP1 DUP4 SLOAD DIV MUL DUP4 MSTORE SWAP2 PUSH1 0x20 ADD SWAP2 PUSH2 0x340 JUMP JUMPDEST CALLER PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x1 PUSH1 0x20 MSTORE PUSH1 0x40 DUP2 KECCAK256 SLOAD DUP3 GT ISZERO PUSH2 0x582 JUMPI PUSH1 0x0 DUP1 REVERT JUMPDEST CALLER PUSH1 0x0 DUP2 DUP2 MSTORE PUSH1 0x1 PUSH1 0x20 SWAP1 DUP2 MSTORE PUSH1 0x40 DUP1 DUP4 KECCAK256 DUP1 SLOAD DUP8 SWAP1 SUB SWAP1 SSTORE PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB DUP8 AND DUP1 DUP5 MSTORE SWAP3 DUP2 SWAP1 KECCAK256 DUP1 SLOAD DUP8 ADD SWAP1 SSTORE DUP1 MLOAD DUP7 DUP2 MSTORE SWAP1 MLOAD SWAP3 SWAP4 SWAP3 PUSH32 0xDDF252AD1BE2C89B69C2B068FC378DAA952BA7F163C4A11628F55A4DF523B3EF SWAP3 SWAP2 DUP2 SWAP1 SUB SWAP1 SWAP2 ADD SWAP1 LOG3 POP PUSH1 0x1 SWAP3 SWAP2 POP POP JUMP JUMPDEST PUSH1 0x1 PUSH1 0xA0 PUSH1 0x2 EXP SUB SWAP2 DUP3 AND PUSH1 0x0 SWAP1 DUP2 MSTORE PUSH1 0x2 PUSH1 0x20 SWAP1 DUP2 MSTORE PUSH1 0x40 DUP1 DUP4 KECCAK256 SWAP4 SWAP1 SWAP5 AND DUP3 MSTORE SWAP2 SWAP1 SWAP2 MSTORE KECCAK256 SLOAD SWAP1 JUMP STOP LOG1 PUSH6 0x627A7A723058 KECCAK256 ADDRESS 0xa7 0xb1 0xca 0xb7 0x2b 0xc8 CODECOPY CALLCODE 0xc9 SDIV 0xba RETURNDATASIZE PUSH7 0x561D6C4F9A1642 REVERT 0x5e CALLER CALLCODE POP SWAP10 0xdf PUSH10 0x55828E00290000000000 ", "sourceMap": "60:2372:1:-;;;417:648;8:9:-1;5:2;;;30:1;27;20:12;5:2;417:648:1;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;591:10;582:20;;;;:8;:20;;;;;:37;;;682:28;;;;417:648;;;766:17;;417:648;;;;;;;;;766:17;;:4;;:17;;;;:::i;:::-;-1:-1:-1;864:8:1;:24;;-1:-1:-1;;864:24:1;;;;;;;968:21;;;;:6;;:21;;;;;:::i;:::-;;417:648;;;;60:2372;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;-1:-1:-1;60:2372:1;;;-1:-1:-1;60:2372:1;:::i;:::-;;;:::o;:::-;;;;;;;;;;;;;;;;;;;;:::o;:::-;;;;;;;” }