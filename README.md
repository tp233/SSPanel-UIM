# SSPanel-UIM

## 1.SSPanel-UIM新版获取用户信息方法：
  ![telegram-cloud-photo-size-4-5915752838590479504-y](https://user-images.githubusercontent.com/122682995/212477583-ac619081-8062-48bd-845f-bf242e775d61.jpg)
新版ssp对接客户端获取用户信息代码，不仅可以对接morck客户端，还可以对接其他客户端。

版权归：SSPanel所有，我只是搬运工

$morck_user_info = $request->getParam('morck_user_info');
        if ($morck_user_info != '') {
            $user = $this->user;
            return $response->withJson([
                'ret' => 1,
                'msg' => $user,
            ]);
        }
