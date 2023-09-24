# UnitySingletonMono
Easy to use, Singleton behaviors for unity.
```
/// <summary>
    /// Called on Instance or None instance Awake
    /// </summary>
    protected virtual void OnAnyAwake() { }  
    /// <summary>
    /// Called when Instance or None instance destroy
    /// </summary>
    protected virtual void OnAnyDestroy() { }
    /// <summary>
    /// alled when this object is set to Instance of <typeparamref name="T"></typeparamref>
    /// </summary>
	protected virtual void OnInstanceSet() {}
    /// <summary>
    /// Called when this Instance object is disabled
    /// </summary>
    protected virtual void OnInstanceDisabled() { }
    /// <summary>
    /// Called when this object is no longer the Instance object.
    /// </summary>
    protected virtual void OnInstanceRemoved() { }
    /// <summary>
    /// Called when this instance object is destroyed
    /// </summary>
    protected virtual void OnInstanceDestroy() { }
    /// <summary>
    /// Called when this instance object is enabled
    /// </summary>
    protected virtual void OnInstanceEnabled() { }
    /// <summary>
    /// Called when none instance object is enabled
    /// </summary>
    protected virtual void OnNoneInstanceEnabled() { }
    /// <summary>
    /// Called on instance object awake, or when instance was set and instance awake wasn't called.
    /// May be called in the editor when <see cref="ForceInstance"/> is called. 
    /// </summary>
    protected virtual void OnInstanceAwake() { }
    /// <summary>
    /// Called on none instance awake
    /// </summary>
    protected virtual void OnNoneInstanceAwake() { }
```
