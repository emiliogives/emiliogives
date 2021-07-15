while(me.Here())
{
  string ask;
  if(
    ask.Contains("about Xamarin") ||
    ask.Contains("about .NET") || 
    ask.Contains("about Python") ||
    ask.Contains("about Powershell") ||
    ask.Contains("about Bash")
    )
    {
      me.Happy2Help(ask);
    }
  else
  {
    me.Learn(ask);
  }   
} 
