<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>ランダムフォームジャンプ</title>
  <script>
    window.onload = function() {
      const forms = [
        "https://docs.google.com/forms/d/e/1FAIpQLSf9oN5E9hR-FO4Q1cRjefAqfKQwtwEf4yGMjWRZsw-Dr0auuQ/viewform?usp=dialog",
        "https://docs.google.com/forms/d/e/1FAIpQLSep-T_3erMh51Dwr-dEEY8fW09NNHRnRDawh1ffURM3-WR1UA/viewform?usp=dialog"
      ];
      const randomIndex = Math.floor(Math.random() * forms.length);
      window.location.href = forms[randomIndex];
    }
  </script>
</head>
<body>
  <p>ランダムにフォームに移動中です。少々お待ちください…</p>
</body>
</html>
