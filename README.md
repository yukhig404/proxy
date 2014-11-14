proxy
=====

RandomにWorkingでEliteなProxyのIPaddressとPortをGetするためのクラス

    $hoge = new Proxy();
    $hoge->setRandomProxyAndPort();
    echo('Proxy => '.$hoge->getProxy());
    echo('Port => '.$hoge->getPort());
