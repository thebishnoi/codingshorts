plugin function use in template ways


class myClassName
{
  function __construct()
    {
      add_action('MY_HOOK_NAME', array($this, 'MY_HOOK_FUNCTION'));
    }
  function MY_HOOK_FUNCTION()
    { // FUNCTION HERE }
} // class






and then use do_shortcode() for this function


another way is to create a shortcode for function and then use it it another function
