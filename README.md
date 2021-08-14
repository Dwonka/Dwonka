/**                                                                                  

DOGE WONKA!!! 

 We love cooking and technology,         /) (\     *SHE IS HAPPY EATING*
 which is why we present here the       ((,,,))   /
 the first reflection and            ,//((((((\\.
 chocolate token at the same time.   (((  ^ ^  )))
 Every purchase gets tastier...      ))))  -   ((((
 with the repurchase                (()(\ )-( /))()
 and hyperdeflation system.         ))))/`-\~\'((((
                                   ((( \/==\_\ <----Dogewonka
                                           {  `.
                                            `-j \
 Oompa Loompa, do-ba-dee-doo,
 I've got a perfect puzzle for you.
 Oompa Loompa, do-ba-dee-dee...


 telegram:
 

*/

// SPDX-License-Identifier: Unlicensed

pragma solidity ^0.8.4;

abstract contract Context {
    function _msgSender() internal view virtual returns (address payable) {
        return payable(msg.sender);
    }

    function _msgData() internal view virtual returns (bytes memory) {
        this; // silence state mutability warning without generating bytecode - see https://github.com/ethereum/solidity/issues/2691
        return msg.data;
    }
}



