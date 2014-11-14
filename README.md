proxy
=====

RandomにWorkingでEliteなProxyをGetするためのクラス

    $hoge = new Proxy();
    $hoge->setRandomProxyAndPort();
    echo('Proxy => '.$hoge->getProxy());
    echo('Port => '.$hoge->getPort());
