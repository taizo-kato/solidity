Solidity
========

.. image:: logo.svg
    :width: 120px
    :alt: Solidity logo
    :align: center

Solidityはスマートコントラクトを扱えるオブジェクト指向の高級言語です。スマートコントラクトはEthereum内でアカウントの動作を制御するものです。

SolidityはC++、Python、JavaScriptを参考に、Ethereum Virtual Machine（EVM）の操作を目的に作られています。

Solidityは静的言語で継承やライブラリ、ユーザーが定義した複雑な他の特徴があります。

Solidityで投票やクラウドファンディング、匿名のオークションやマルチシグウォレットを作成することができます。

コントラクトをデプロイする際には最新バージョンのSolidityを使うことが推奨されています。これは新しい機能やバグ修正に加えbreaking changesが定期的に導入されているためです。現在0.xバージョン

Language Documentation
----------------------

もしスマートコントラクトというコンセプトが初めてなのであればSolidityで書かれた:ref:`an example smart contract <simple-smart-contract>`を推奨します。もっと詳細な情報が欲しい場合は :doc:`"Solidity by Example" <solidity-by-example>` and :doc:`"Solidity in Depth" <solidity-in-depth>`セクションを読むことをお勧めします。

.. hint::
`Remix IDE <https://remix.ethereum.org>`_でいつでもサンプルコードを試すことができます。RemixはブラウザベースのIDEでSolidityでスマートコントラクトが書け、デプロイしてスマートコントラクトを動かすことができます。しばらく時間がかかる場合もありますが、気長にお待ちください。

.. warning::
人間がコードを書いていますのでバグが発生する可能性があります。スマートコントラクトを書く際にはソフトウェア開発のベストプラクティスを参照することをお勧めします。このベストプラクティスはコードレビュー、テスト、audits、correctness proofsを含んでいます。スマートコントラクトのユーザーは時に作成者よりコードそのものを信用します。そしてブロックチェーンとスマートコントラクトはそれぞれ注意すべき特有の問題を抱えているため、production codeに取り掛かる前に:ref:`security_considerations`セクションを参照してください。

もし疑問があれば、`Ethereum Stackexchange <https://ethereum.stackexchange.com/>`_か`gitter channel <https://gitter.im/ethereum/solidity/>`_で検索もしくは質問してください。

Solidityやこのドキュメントをより良くするアイデアはいつでも大歓迎です。詳細は:doc:`contributors guide <contributing>`を参照ください。

Translations
------------

コミュニティのボランティアがこのドキュメントの翻訳をいくつかの言語で行なっています。進捗具合は言語によって異なりますが、英語のバージョンがリファレンスとして使われています。

* `中国語 <http://solidity-cn.readthedocs.io>`_ (in progress)
* `スペイン語 <https://solidity-es.readthedocs.io>`_
* `ロシア語 <https://github.com/ethereum/wiki/wiki/%5BRussian%5D-%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BF%D0%BE-Solidity>`_ (rather outdated)
* `韓国語 <http://solidity-kr.readthedocs.io>`_ (in progress)
* `フランス語 <http://solidity-fr.readthedocs.io>`_ (in progress)

Contents
========

:ref:`Keyword Index <genindex>`, :ref:`Search Page <search>`

.. toctree::
   :maxdepth: 2

   introduction-to-smart-contracts.rst
   installing-solidity.rst
   solidity-by-example.rst
   solidity-in-depth.rst
   security-considerations.rst
   resources.rst
   using-the-compiler.rst
   metadata.rst
   abi-spec.rst
   yul.rst
   style-guide.rst
   common-patterns.rst
   bugs.rst
   contributing.rst
   frequently-asked-questions.rst
   lll.rst
